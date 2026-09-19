<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy8-t-bnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wy8-t-bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:glowing-hands" /></template>

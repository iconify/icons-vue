<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg6l1rb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hg6l1rb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:at-sea" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y87p7zb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y87p7zb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fog" /></template>

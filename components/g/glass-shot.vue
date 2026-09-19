<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm4x219yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bm4x219yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:glass-shot" /></template>

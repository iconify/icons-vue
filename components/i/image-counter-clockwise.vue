<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s4xf7_lqd.css';
import '../../css/b/b4h22tbjt.css';
import '../../css/i/imbmv_-3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s4xf7_lqd"/><path class="b4h22tbjt"/><path class="imbmv_-3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:image-counter-clockwise" /></template>

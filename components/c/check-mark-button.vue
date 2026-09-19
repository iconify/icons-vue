<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h_bhhd9ki.css';
import '../../css/u/uru88vgdy.css';
import '../../css/l/lms1l_bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="h_bhhd9ki"/><path class="uru88vgdy"/><path class="lms1l_bwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:check-mark-button" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij2x_72vy.css';
import '../../css/z/zz1s_3qhb.css';
import '../../css/c/cswrng7jb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="ij2x_72vy"><path class="zz1s_3qhb"/><path class="cswrng7jb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:last-track-button" /></template>

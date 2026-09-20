<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zym40bb_i.css';
import '../../css/s/snl4_j1oh.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/u/u9ce-33wr.css';
import '../../css/h/h0--35b1u.css';
import '../../css/f/fordnus3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zym40bb_i"/><path class="snl4_j1oh"/><g class="ij2x_72vy"><path class="u9ce-33wr"/><path class="h0--35b1u"/><path class="fordnus3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:folded-hands-medium-skin-tone" /></template>

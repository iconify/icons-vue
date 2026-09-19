<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z67_wkbeg.css';
import '../../css/q/qvp7rrb8e.css';
import '../../css/d/dpcaptc_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="z67_wkbeg"/><path class="qvp7rrb8e"/><path class="dpcaptc_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:book-duo" /></template>

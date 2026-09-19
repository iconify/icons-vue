<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wk69wgvme.css';
import '../../css/y/y0tn1610r.css';
import '../../css/y/ys10sbcwu.css';
import '../../css/f/fd3mxjbhi.css';
import '../../css/s/sw6xrrosx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="wk69wgvme"/><path clip-rule="evenodd" class="y0tn1610r"/><path class="ys10sbcwu"/><path clip-rule="evenodd" class="fd3mxjbhi"/><path class="sw6xrrosx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:helicopter-bold" /></template>

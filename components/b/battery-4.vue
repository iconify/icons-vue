<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ie49pn7lv.css';
import '../../css/r/rlafmm9-k.css';
import '../../css/y/yspwoqr-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ie49pn7lv"/><path class="rlafmm9-k"/><path clip-rule="evenodd" class="yspwoqr-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:battery-4" /></template>

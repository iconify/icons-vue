<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z78iq229s.css';
import '../../css/e/e37y0sbcn.css';
import '../../css/m/mig00zq1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="z78iq229s"/><path clip-rule="evenodd" class="e37y0sbcn"/><path class="mig00zq1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:film" /></template>

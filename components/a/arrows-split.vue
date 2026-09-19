<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cy_-d12mf.css';
import '../../css/z/z89d9tfpr.css';
import '../../css/h/hu4hk-xvr.css';
import '../../css/k/k4_h-ab8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="cy_-d12mf"/><path class="z89d9tfpr"/><path class="hu4hk-xvr"/><path class="k4_h-ab8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:arrows-split" /></template>

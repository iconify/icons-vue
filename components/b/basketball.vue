<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/khxma8kyi.css';
import '../../css/h/hsdwt973y.css';
import '../../css/s/stgidx8-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="khxma8kyi"/><path clip-rule="evenodd" class="hsdwt973y"/><path clip-rule="evenodd" class="stgidx8-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:basketball" /></template>

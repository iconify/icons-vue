<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/am770-rkn.css';
import '../../css/m/mqa4firwe.css';
import '../../css/h/hyc9jcbmb.css';
import '../../css/d/ducbzu09b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="am770-rkn"/><path clip-rule="evenodd" class="mqa4firwe"/><circle class="hyc9jcbmb"/><path class="ducbzu09b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:laugh-wink" /></template>

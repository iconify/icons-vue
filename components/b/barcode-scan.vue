<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aq0r-rk9e.css';
import '../../css/i/imi_ebbbr.css';
import '../../css/r/rlrjkrbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="aq0r-rk9e"/><path class="imi_ebbbr"/><path class="rlrjkrbhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:barcode-scan" /></template>

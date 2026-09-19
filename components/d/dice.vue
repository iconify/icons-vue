<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/e/efh70xbdi.css';
import '../../css/h/hk9y0zedv.css';
import '../../css/i/i0_oy7bap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="efh70xbdi"/><path class="hk9y0zedv"/><path class="i0_oy7bap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:dice" /></template>

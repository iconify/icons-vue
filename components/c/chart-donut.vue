<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/i/ino6mr9nn.css';
import '../../css/s/sn6br5b4i.css';
import '../../css/c/csubeabti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ino6mr9nn"/><path class="sn6br5b4i"/><path class="csubeabti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chart-donut" /></template>

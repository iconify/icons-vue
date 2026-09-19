<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/t/tp0xbbu1o.css';
import '../../css/i/in5jxro8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="tp0xbbu1o"/><path class="in5jxro8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:electric-scooter" /></template>

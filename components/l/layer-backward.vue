<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/u/u8_ot7bnm.css';
import '../../css/b/b7u9enlhv.css';
import '../../css/c/c6-vowhzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="u8_ot7bnm"/><path class="b7u9enlhv"/><path class="c6-vowhzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layer-backward" /></template>

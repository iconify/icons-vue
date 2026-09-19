<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/z/zbmuzbcez.css';
import '../../css/h/hsp2_ccfa.css';
import '../../css/t/tljyajbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="zbmuzbcez"/><path class="hsp2_ccfa"/><path class="tljyajbkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:compass-1" /></template>

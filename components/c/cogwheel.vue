<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/k/ko6ce4blt.css';
import '../../css/w/w9xiptpes.css';
import '../../css/c/cgmljzbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ko6ce4blt"/><path class="w9xiptpes"/><path class="cgmljzbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cogwheel" /></template>

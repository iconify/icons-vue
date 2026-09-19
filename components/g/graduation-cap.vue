<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/j/jo7l1vbem.css';
import '../../css/i/ij91p0ogo.css';
import '../../css/e/e1hw3-b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="jo7l1vbem"/><path class="ij91p0ogo"/><path class="e1hw3-b-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:graduation-cap" /></template>

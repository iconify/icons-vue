<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/t/txtwnjbdf.css';
import '../../css/z/zm17-uvzv.css';
import '../../css/p/p_196_o6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="txtwnjbdf"/><path class="zm17-uvzv"/><path clip-rule="evenodd" class="p_196_o6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:laptop-cog" /></template>

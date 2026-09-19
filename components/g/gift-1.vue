<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/p/pczwx_b9m.css';
import '../../css/i/ieuur3b8f.css';
import '../../css/e/e3091ubgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="pczwx_b9m"/><path class="ieuur3b8f"/><path class="e3091ubgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:gift-1" /></template>

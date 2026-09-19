<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/n/ncr4y8hbl.css';
import '../../css/z/ze5g_h5ii.css';
import '../../css/d/d6uq56b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ncr4y8hbl"/><path class="ze5g_h5ii"/><path class="d6uq56b0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layer-group" /></template>

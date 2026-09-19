<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/w/w-hxk767e.css';
import '../../css/u/uw-n9cbom.css';
import '../../css/h/h35g33bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="w-hxk767e"/><path class="uw-n9cbom"/><path class="h35g33bej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:axe" /></template>

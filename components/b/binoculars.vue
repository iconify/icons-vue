<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/v/v98yaftnr.css';
import '../../css/w/wyzcj9bru.css';
import '../../css/y/yp56kod4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="v98yaftnr"/><path class="wyzcj9bru"/><path class="yp56kod4q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:binoculars" /></template>

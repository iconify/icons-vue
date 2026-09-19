<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s-ld4nbiy.css';
import '../../css/w/wzylqhcvh.css';
import '../../css/m/mxv273bqu.css';
import '../../css/m/m4zk6ezvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="s-ld4nbiy"/><path class="wzylqhcvh"/><path clip-rule="evenodd" class="mxv273bqu"/><path clip-rule="evenodd" class="m4zk6ezvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:keycap" /></template>

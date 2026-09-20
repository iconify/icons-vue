<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekdg5ur0t.css';
import '../../css/y/yor81gb5d.css';
import '../../css/u/u4_g3v0-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ekdg5ur0t"/><ellipse class="yor81gb5d"/><path class="u4_g3v0-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:atm" /></template>

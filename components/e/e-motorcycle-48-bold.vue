<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hliyo-bto.css';
import '../../css/p/pxuausb5x.css';
import '../../css/v/vy9bxel0f.css';
import '../../css/r/ra4sd8ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hliyo-bto"/><path class="pxuausb5x"/><path class="vy9bxel0f"/><path class="ra4sd8ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:e-motorcycle-48-bold" /></template>

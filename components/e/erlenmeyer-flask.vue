<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/s/shlcypgis.css';
import '../../css/p/pi3qt6bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="shlcypgis"/><path class="pi3qt6bpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:erlenmeyer-flask" /></template>

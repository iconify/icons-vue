<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qccsvpbeb.css';
import '../../css/a/a2by68ltf.css';
import '../../css/c/csbdrc94y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="qccsvpbeb"/><path class="a2by68ltf"/><path class="csbdrc94y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:camera-noflash" /></template>

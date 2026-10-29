<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hkz12t8dl.css';
import '../../css/s/svkvmye9m.css';
import '../../css/t/tf9_0-uqj.css';
import '../../css/h/h-upcp83y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hkz12t8dl wm-k"/><path class="svkvmye9m wm-shadow"/><path class="tf9_0-uqj wm-k"/><path class="h-upcp83y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hexagon-engrave" /></template>

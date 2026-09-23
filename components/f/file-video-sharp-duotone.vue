<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/vpyvtnijy.css';
import '../../css/g/g6hnddcux.css';
import '../../css/d/denm83b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vpyvtnijy"/><path clip-rule="evenodd" class="g6hnddcux"/><path class="denm83b6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-video-sharp-duotone" /></template>

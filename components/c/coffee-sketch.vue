<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tyqgt9b1c.css';
import '../../css/p/pue4fnbwj.css';
import '../../css/m/mc70u-h4x.css';
import '../../css/w/wtj99vbvi.css';
import '../../css/x/xn284ibso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tyqgt9b1c"/><path class="pue4fnbwj wm-k"/><path class="mc70u-h4x wm-a"/><path class="wm-k wtj99vbvi"/><path class="wm-a xn284ibso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:coffee-sketch" /></template>

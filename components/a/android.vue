<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vk0-50wrr.css';
import '../../css/u/u-115phol.css';
import '../../css/t/tbj7xn_hc.css';
import '../../css/n/nvkuv6u_b.css';
import '../../css/d/dedtfabrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="vk0-50wrr"/><path class="u-115phol"/><path class="tbj7xn_hc"/><circle class="nvkuv6u_b"/><circle class="dedtfabrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:android" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbo_5h3_g.css';
import '../../css/a/aohc2wbew.css';
import '../../css/h/hss_7gbmm.css';
import '../../css/w/wb3b4xbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fbo_5h3_g"/><path class="aohc2wbew"/><path class="hss_7gbmm"/><path class="wb3b4xbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-queue-48" /></template>

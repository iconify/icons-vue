<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/far_cdbom.css';
import '../../css/v/vmzs2cilw.css';
import '../../css/r/rfghtubvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect transform="rotate(-45 312.002 311.994)" class="far_cdbom"/><path class="vmzs2cilw"/><path class="rfghtubvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:color-wand-outline" /></template>

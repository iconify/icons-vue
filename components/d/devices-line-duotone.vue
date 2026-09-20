<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qwzcgabfh.css';
import '../../css/a/atcwzkbau.css';
import '../../css/i/ij-ylgbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qwzcgabfh"/><path class="atcwzkbau"/><path class="ij-ylgbkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:devices-line-duotone" /></template>

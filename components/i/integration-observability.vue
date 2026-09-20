<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnu9x_btz.css';
import '../../css/u/uf4j-xoii.css';
import '../../css/k/kk9m20bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qnu9x_btz"/><path clip-rule="evenodd" class="uf4j-xoii"/><path clip-rule="evenodd" class="kk9m20bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:integration-observability" /></template>

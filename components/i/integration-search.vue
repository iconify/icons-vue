<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnu9x_btz.css';
import '../../css/k/koyp8_atq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qnu9x_btz"/><path class="koyp8_atq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:integration-search" /></template>

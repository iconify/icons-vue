<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8_cpacsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="h8_cpacsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-crossover-up-cross-move-over-arrow-arrows-right" /></template>

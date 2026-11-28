<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_x0n2pbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_x0n2pbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bar-chart-horizontal-solid" /></template>

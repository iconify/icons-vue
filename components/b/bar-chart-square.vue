<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpd3nyb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpd3nyb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:bar-chart-square" /></template>

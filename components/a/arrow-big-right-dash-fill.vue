<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwtugtb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwtugtb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-big-right-dash-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oub0p0bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oub0p0bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-scatter-fill" /></template>

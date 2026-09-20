<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh1y9gbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh1y9gbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flow-chart" /></template>

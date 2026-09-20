<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko0j1x2yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko0j1x2yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-pie-two-solid" /></template>

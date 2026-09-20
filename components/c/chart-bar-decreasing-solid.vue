<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_46b9bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_46b9bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-bar-decreasing-solid" /></template>

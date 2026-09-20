<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8b-o5wtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8b-o5wtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-pie-two" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn2_-vbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn2_-vbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chart-no-axes-column-increasing-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv-dhlzga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv-dhlzga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:battery-full-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xax2ld-hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xax2ld-hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-chart-column-increasing" /></template>

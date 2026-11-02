<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbth6abaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbth6abaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:inspection-panel-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt-6ugbcf.css';
import '../../css/w/wm3j448rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wt-6ugbcf"/><path class="wm3j448rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-chart-bold" /></template>

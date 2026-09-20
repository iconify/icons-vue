<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hofylubij.css';
import '../../css/x/xq1vpwbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hofylubij"/><path clip-rule="evenodd" class="xq1vpwbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:keyboard" /></template>

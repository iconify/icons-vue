<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubzqx4l4f.css';
import '../../css/d/dfj0wcpcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubzqx4l4f"/><path class="dfj0wcpcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-pie-3-line" /></template>

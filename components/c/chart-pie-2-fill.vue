<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djfjsab7t.css';
import '../../css/m/mj8r-ibdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djfjsab7t"/><path class="mj8r-ibdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-pie-2-fill" /></template>

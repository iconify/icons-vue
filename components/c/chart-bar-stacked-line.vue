<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4li52eld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4li52eld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-bar-stacked-line" /></template>

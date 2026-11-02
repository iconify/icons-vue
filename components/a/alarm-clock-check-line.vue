<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxdsqgbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxdsqgbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alarm-clock-check-line" /></template>

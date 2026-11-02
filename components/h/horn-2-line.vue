<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5izf94kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5izf94kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:horn-2-line" /></template>

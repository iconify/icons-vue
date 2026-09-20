<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jraks8bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jraks8bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cigarette-off" /></template>

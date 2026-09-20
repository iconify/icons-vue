<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcq7k6bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcq7k6bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:alarm-clock-x" /></template>

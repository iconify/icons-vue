<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8_3b8ifa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8_3b8ifa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-big-left" /></template>

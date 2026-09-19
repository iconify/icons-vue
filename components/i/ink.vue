<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd3uhsi3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd3uhsi3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:ink" /></template>

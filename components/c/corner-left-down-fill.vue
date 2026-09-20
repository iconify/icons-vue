<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su8yfj8iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su8yfj8iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:corner-left-down-fill" /></template>

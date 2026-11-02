<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp8d2ookr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp8d2ookr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gift-card-fill" /></template>

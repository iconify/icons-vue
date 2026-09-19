<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wupi-6bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wupi-6bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:buddicons-topics" /></template>

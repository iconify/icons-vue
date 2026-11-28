<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqqnc8b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tqqnc8b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-clock-light" /></template>

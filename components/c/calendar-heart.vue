<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd8mj3bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd8mj3bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-heart" /></template>

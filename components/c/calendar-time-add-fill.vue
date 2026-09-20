<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzu-h2-ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzu-h2-ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-time-add-fill" /></template>

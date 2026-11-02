<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0mrpebth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0mrpebth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-month-fill" /></template>

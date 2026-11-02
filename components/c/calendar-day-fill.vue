<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkeo3w_2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkeo3w_2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-day-fill" /></template>

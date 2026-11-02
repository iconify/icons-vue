<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua1radb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua1radb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-x-line" /></template>

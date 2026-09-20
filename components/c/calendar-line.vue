<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i51-s6bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i51-s6bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-line" /></template>

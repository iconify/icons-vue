<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slep1f0fb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slep1f0fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-off-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ochedyccx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ochedyccx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-week-round" /></template>

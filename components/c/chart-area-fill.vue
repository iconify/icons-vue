<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo5xe0b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo5xe0b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-area-fill" /></template>

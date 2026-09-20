<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qycvaefki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qycvaefki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-week-line" /></template>

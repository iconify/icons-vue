<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3wdkibzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3wdkibzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-time-add-line" /></template>

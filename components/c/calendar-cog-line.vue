<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyrd1732q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyrd1732q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-cog-line" /></template>

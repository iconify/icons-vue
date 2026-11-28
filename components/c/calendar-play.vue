<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of__6dbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of__6dbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:calendar-play" /></template>

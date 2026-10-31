<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jol785xfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jol785xfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-round" /></template>

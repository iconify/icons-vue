<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytk0fdbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytk0fdbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:calendar-mark" /></template>

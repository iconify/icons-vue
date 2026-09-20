<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc_ox0uwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc_ox0uwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:calendar-todo-fill" /></template>

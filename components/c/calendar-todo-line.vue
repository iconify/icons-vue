<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7c5r0k6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7c5r0k6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:calendar-todo-line" /></template>

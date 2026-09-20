<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsk0oibtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsk0oibtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:calendar-check-line" /></template>

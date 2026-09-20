<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruyz_z9xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruyz_z9xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-week-fill" /></template>

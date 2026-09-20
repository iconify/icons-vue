<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th1qi9bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th1qi9bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-plus" /></template>

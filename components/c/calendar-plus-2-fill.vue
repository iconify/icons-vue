<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t60pv0b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t60pv0b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-plus-2-fill" /></template>

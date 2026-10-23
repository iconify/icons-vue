<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fozb4jemz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fozb4jemz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-arrow-down" /></template>

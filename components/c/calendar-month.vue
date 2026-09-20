<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq2nzl86u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq2nzl86u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-month" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmum_5bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmum_5bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-sort-ascending" /></template>

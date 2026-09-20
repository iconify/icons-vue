<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtv4w57nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtv4w57nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-account" /></template>

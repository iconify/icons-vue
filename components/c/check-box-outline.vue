<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-lwxf4od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-lwxf4od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:check-box-outline" /></template>

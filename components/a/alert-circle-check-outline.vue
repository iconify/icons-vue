<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3-25i8ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3-25i8ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alert-circle-check-outline" /></template>

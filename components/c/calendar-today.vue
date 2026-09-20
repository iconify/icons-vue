<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nosv9sbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nosv9sbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-today" /></template>

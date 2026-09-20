<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw0pxcbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw0pxcbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-filter" /></template>

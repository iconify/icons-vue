<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbkzq4bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbkzq4bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-collapse-horizontal-outline" /></template>

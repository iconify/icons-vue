<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3h0oiboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3h0oiboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-tick-outline" /></template>

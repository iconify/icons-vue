<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0mqs7bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0mqs7bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cookie-clock-outline" /></template>

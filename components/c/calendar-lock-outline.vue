<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejy92px3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejy92px3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-lock-outline" /></template>

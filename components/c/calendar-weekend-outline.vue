<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r33v170sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r33v170sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-weekend-outline" /></template>

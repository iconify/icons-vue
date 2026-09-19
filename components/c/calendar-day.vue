<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu36i1b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zu36i1b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:calendar-day" /></template>

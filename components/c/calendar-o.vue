<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f56opvbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="f56opvbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:calendar-o" /></template>

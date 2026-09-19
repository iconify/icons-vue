<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gma850bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="gma850bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:calendar-plus-o" /></template>

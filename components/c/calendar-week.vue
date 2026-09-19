<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2swmfb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="r2swmfb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:calendar-week" /></template>

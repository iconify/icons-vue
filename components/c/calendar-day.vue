<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwojc847m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lwojc847m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:calendar-day" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aum7pfzqi.css';
import '../../css/c/c4va-acpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aum7pfzqi"/><path class="c4va-acpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-range-20-bold" /></template>

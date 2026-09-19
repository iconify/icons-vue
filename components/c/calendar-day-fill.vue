<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glq9k8b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="glq9k8b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calendar-day-fill" /></template>

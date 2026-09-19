<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abeen-81d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="abeen-81d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calendar-range-fill" /></template>

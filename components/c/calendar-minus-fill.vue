<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1ilmacnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e1ilmacnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calendar-minus-fill" /></template>

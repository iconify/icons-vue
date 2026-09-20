<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayg99-b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ayg99-b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:hanger" /></template>

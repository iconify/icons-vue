<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siks4l5qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="siks4l5qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:calendar-fill-16" /></template>

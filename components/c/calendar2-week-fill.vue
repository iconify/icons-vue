<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jceo9d0_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jceo9d0_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calendar2-week-fill" /></template>

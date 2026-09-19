<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef_45p5km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ef_45p5km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:egg-fill" /></template>

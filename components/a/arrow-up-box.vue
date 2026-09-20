<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt_364k4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="rt_364k4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-up-box" /></template>

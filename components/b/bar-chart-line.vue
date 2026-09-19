<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omuhb1bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="omuhb1bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bar-chart-line" /></template>

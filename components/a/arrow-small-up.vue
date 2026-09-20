<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy4q2qsdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":6,"height":16};
const content = `<path class="wy4q2qsdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-small-up" /></template>

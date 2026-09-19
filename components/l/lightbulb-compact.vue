<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewydz64iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ewydz64iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:lightbulb-compact" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbc025bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rbc025bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:calendar" /></template>

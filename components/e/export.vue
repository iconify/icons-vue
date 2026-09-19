<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx1f7dbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vx1f7dbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:export" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib6l7jmqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ib6l7jmqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-step-out" /></template>

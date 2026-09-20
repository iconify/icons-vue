<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3wbsm0fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z3wbsm0fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:editor-table" /></template>

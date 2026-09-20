<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5kjy4_hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o5kjy4_hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:kusto" /></template>

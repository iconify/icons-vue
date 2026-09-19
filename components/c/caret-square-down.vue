<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln8uiccjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ln8uiccjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:caret-square-down" /></template>

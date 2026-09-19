<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzkm26lyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hzkm26lyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-blank-stroke-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3y7s6guh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j3y7s6guh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:caret-sort-up" /></template>

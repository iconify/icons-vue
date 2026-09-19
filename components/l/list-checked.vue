<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmao-rbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dmao-rbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:list-checked" /></template>

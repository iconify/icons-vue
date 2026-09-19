<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0g1hvbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p0g1hvbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:erase" /></template>

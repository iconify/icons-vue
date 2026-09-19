<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2znugpwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z2znugpwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-right-01" /></template>

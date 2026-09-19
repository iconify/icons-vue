<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7_v91bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d7_v91bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:asm" /></template>

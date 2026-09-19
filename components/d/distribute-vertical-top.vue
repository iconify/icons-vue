<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiwn7b8vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oiwn7b8vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:distribute-vertical-top" /></template>

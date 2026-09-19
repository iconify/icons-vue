<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-mit6byn.css';
import '../../css/c/cro928b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l-mit6byn"/><path class="cro928b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:inventory-management" /></template>

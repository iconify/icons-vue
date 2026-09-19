<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj8ezo3zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uj8ezo3zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calls-all" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwrczlbqy.css';
import '../../css/g/g-8u0m53a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rwrczlbqy"/><path class="g-8u0m53a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-monitoring" /></template>

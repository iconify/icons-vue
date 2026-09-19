<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3tfc2boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q3tfc2boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arrows" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkjb6_06b.css';
import '../../css/y/y--yqbbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nkjb6_06b"/><path class="y--yqbbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-loop-left" /></template>

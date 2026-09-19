<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5fox30if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j5fox30if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:interface-usage-1" /></template>

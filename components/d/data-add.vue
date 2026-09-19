<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbjht8bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kbjht8bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-add" /></template>

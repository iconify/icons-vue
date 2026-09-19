<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5nekx9ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t5nekx9ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:add-parent-node" /></template>

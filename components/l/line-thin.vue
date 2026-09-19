<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7hje7b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o7hje7b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:line-thin" /></template>

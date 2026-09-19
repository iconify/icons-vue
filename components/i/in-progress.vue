<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc32occtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tc32occtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:in-progress" /></template>

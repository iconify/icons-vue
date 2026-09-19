<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eteeavbsa.css';
import '../../css/i/izeh2ywyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eteeavbsa"/><path class="izeh2ywyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:category-add" /></template>

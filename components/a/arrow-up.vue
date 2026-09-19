<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/entb44w_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="entb44w_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arrow-up" /></template>

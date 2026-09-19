<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns7q5-h7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ns7q5-h7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:curved-line-dashed" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkgkj5b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kkgkj5b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-knowledge-catalog" /></template>

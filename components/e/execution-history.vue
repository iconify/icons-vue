<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqv9ttb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tqv9ttb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:execution-history" /></template>

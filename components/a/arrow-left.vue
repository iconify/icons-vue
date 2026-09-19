<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek6lbbb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ek6lbbb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arrow-left" /></template>

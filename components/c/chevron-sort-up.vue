<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7wdrcc7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m7wdrcc7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chevron-sort-up" /></template>

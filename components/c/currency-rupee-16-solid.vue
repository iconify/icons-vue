<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fszv21x0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fszv21x0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:currency-rupee-16-solid" /></template>

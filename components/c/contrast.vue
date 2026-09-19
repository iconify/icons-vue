<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo40o4bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eo40o4bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:contrast" /></template>

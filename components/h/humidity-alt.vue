<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulp2to6dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ulp2to6dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:humidity-alt" /></template>

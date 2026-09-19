<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/magta5rkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="magta5rkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:departure" /></template>

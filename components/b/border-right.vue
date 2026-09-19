<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_2mddbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e_2mddbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:border-right" /></template>

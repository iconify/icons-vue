<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eabxhopre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1312};
const content = `<path class="eabxhopre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:chevron-down" /></template>

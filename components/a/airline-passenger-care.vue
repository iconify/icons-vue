<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjvnk_omj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xjvnk_omj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:airline-passenger-care" /></template>

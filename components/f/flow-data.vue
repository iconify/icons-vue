<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsj0y6bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xsj0y6bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flow-data" /></template>

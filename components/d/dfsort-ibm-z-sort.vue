<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5djkcoxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c5djkcoxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:dfsort-ibm-z-sort" /></template>

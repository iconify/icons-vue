<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0ku6lcmx.css';
import '../../css/l/lruer8ufr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o0ku6lcmx"/><path class="lruer8ufr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-unstructured" /></template>

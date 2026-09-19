<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d58vsbvrf.css';
import '../../css/v/v7mge4i6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d58vsbvrf"/><path class="v7mge4i6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-knowledge-catalog" /></template>

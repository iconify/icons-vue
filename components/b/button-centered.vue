<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7knn_bjg.css';
import '../../css/k/ksmczrn_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j7knn_bjg"/><path class="ksmczrn_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:button-centered" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5qe6qp3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x5qe6qp3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:element-picker" /></template>

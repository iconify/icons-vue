<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3d_qp7ez.css';
import '../../css/m/ml-m03v8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z3d_qp7ez"/><path clip-rule="evenodd" class="ml-m03v8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:boolean-substract-16" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrtzwyj8v.css';
import '../../css/i/iiwuq1b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lrtzwyj8v"/><path class="iiwuq1b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:folder-add" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptz7ttbgp.css';
import '../../css/d/dlkylf--k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ptz7ttbgp"/><path class="dlkylf--k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-lqe" /></template>

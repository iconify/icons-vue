<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n38-vj_wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":14};
const content = `<path class="n38-vj_wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:accessibility" /></template>

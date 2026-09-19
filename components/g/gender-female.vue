<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl_0jwbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cl_0jwbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:gender-female" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0coq4_wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n0coq4_wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:gear-wide-connected" /></template>

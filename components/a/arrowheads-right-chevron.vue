<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex_e1-b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ex_e1-b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-right-chevron" /></template>

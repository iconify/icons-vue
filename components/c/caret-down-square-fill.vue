<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3nac-40h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z3nac-40h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:caret-down-square-fill" /></template>

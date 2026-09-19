<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t69zzmbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t69zzmbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud" /></template>

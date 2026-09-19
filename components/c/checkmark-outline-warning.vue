<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgj8co51w.css';
import '../../css/o/o_xa80bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kgj8co51w"/><path class="o_xa80bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:checkmark-outline-warning" /></template>

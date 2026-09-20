<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kthkzmbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kthkzmbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:bookmark-copy-2" /></template>

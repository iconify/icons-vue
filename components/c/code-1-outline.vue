<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-3s45tqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="k-3s45tqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:code-1-outline" /></template>

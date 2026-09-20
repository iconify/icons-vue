<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdqndbb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qdqndbb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:circle-check" /></template>

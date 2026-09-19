<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg9qp9bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg9qp9bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:home-minus" /></template>

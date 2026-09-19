<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs6osbb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zs6osbb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:load-balancer-network" /></template>

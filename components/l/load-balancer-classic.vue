<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_nn80bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b_nn80bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:load-balancer-classic" /></template>

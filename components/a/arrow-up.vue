<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3inu9bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t3inu9bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:arrow-up" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epxn97bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="epxn97bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrows-to-eye" /></template>

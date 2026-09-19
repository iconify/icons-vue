<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovc8f6blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ovc8f6blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:left-arrow" /></template>

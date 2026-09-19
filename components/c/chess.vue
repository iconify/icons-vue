<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oppzb9fsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="oppzb9fsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:chess" /></template>

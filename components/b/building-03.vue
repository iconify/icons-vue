<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy8lnwbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy8lnwbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:building-03" /></template>

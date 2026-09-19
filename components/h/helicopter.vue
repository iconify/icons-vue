<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nffkr1bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nffkr1bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:helicopter" /></template>

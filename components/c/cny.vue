<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yifwj2bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yifwj2bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:cny" /></template>

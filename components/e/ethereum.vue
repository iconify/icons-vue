<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk54w8rpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hk54w8rpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ethereum" /></template>

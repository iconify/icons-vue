<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxavxbbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hxavxbbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:category-and" /></template>

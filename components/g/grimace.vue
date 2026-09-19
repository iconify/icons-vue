<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm9ypbioh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sm9ypbioh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:grimace" /></template>

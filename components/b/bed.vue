<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yih36_51r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yih36_51r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bed" /></template>

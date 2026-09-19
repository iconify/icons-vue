<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8tscxbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="c8tscxbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:border-top-left" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fniq62c1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fniq62c1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:finish-flag" /></template>

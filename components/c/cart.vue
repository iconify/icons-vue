<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0i-0-khj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i0i-0-khj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:cart" /></template>

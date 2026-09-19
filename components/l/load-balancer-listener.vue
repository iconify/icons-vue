<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4v3vwb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c4v3vwb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:load-balancer-listener" /></template>

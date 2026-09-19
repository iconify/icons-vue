<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfy3efzhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tfy3efzhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:load-balancer-local" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3k8zedlj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="m3k8zedlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:die-six" /></template>

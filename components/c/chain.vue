<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr3u_81nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dr3u_81nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:chain" /></template>

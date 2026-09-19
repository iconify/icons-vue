<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuf0csw1g.css';
import '../../css/y/y3x4cnbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wuf0csw1g"/><path class="y3x4cnbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-foundry-1" /></template>

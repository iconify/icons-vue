<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs1p27bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fs1p27bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:aerospike-wordmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvsna5bbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="dvsna5bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:ethereum" /></template>

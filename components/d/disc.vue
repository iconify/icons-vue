<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc0gd3b0i.css';
import '../../css/d/d3_4f-5he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pc0gd3b0i"/><path class="d3_4f-5he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:disc" /></template>

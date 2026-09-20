<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwyjikbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xwyjikbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:drinking-water-14" /></template>

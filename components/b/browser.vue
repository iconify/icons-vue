<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f897x_j9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="f897x_j9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:browser" /></template>

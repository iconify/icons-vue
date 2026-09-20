<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyx02_bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yyx02_bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-down-circle-outline" /></template>

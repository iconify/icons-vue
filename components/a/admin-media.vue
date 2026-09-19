<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvy4j9bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yvy4j9bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-media" /></template>

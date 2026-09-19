<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddgfu5xyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddgfu5xyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:container-optimized-os" /></template>

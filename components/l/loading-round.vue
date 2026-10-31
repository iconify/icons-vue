<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxt7g3rhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxt7g3rhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:loading-round" /></template>

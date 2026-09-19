<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aotbj3bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aotbj3bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:line-graph" /></template>

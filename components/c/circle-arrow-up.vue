<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svjm3hclv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svjm3hclv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:circle-arrow-up" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4bjaccex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4bjaccex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:laptop-check" /></template>

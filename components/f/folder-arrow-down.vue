<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb0yibb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb0yibb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-arrow-down" /></template>

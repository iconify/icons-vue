<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wybhoiqbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wybhoiqbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-arrow-down" /></template>

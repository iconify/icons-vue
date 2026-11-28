<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq3o7-bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq3o7-bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-text-x" /></template>

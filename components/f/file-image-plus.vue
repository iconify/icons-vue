<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frt9vwbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frt9vwbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-image-plus" /></template>

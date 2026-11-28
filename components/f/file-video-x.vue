<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti4624zgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti4624zgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-video-x" /></template>

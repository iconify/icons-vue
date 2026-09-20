<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md78e4_pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="md78e4_pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:loading-spinning-star" /></template>

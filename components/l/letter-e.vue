<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd31yq_fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd31yq_fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-e" /></template>

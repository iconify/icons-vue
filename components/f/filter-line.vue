<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxzt4c83h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxzt4c83h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:filter-line" /></template>

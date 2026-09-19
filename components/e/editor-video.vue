<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oend9i0ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oend9i0ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-video" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq54d0bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vq54d0bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-break" /></template>

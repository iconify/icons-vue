<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af4hf3w3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":472};
const content = `<path class="af4hf3w3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:filter-frames" /></template>

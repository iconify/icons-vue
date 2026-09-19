<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liem6rbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":408};
const content = `<path class="liem6rbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:camera" /></template>

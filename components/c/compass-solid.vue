<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stku8xd3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stku8xd3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:compass-solid" /></template>

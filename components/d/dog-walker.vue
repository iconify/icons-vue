<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b63ho8b4l.css';
import '../../css/v/vqcm1iv2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b63ho8b4l"/><path class="vqcm1iv2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:dog-walker" /></template>

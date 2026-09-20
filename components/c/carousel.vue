<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw6_xbb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="hw6_xbb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:carousel" /></template>

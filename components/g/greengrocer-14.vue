<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6ar3r9kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="z6ar3r9kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:greengrocer-14" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp5oe00ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp5oe00ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:code-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d42b9tbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d42b9tbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:comment-text-sharp" /></template>

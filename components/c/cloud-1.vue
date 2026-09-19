<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmdeh4btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="lmdeh4btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cloud-1" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw9a7ubbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kw9a7ubbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:envelope-front-bold" /></template>

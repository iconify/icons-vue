<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6fegacpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g6fegacpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crown-2-outline" /></template>

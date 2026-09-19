<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg0zrubmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cg0zrubmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:books-outline" /></template>

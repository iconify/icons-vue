<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh_t7actz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vh_t7actz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:book-spine-outline" /></template>

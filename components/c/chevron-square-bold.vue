<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9ys0rl9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="m9ys0rl9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chevron-square-bold" /></template>

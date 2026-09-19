<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1rqt3bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="u1rqt3bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:frown-bold" /></template>

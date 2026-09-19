<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/korhhmbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="korhhmbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:leaf-1-outline" /></template>

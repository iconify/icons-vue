<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-qf5gbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="h-qf5gbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:apple" /></template>

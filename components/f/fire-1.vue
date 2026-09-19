<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg0dvqbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xg0dvqbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:fire-1" /></template>

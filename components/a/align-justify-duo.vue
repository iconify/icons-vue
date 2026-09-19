<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj7gvbxkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jj7gvbxkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-justify-duo" /></template>

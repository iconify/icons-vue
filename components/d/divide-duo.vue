<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4bp8ebol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="b4bp8ebol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:divide-duo" /></template>

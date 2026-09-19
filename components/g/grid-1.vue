<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9o14pb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="p9o14pb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grid-1" /></template>

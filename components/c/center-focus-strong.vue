<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut50qeh6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ut50qeh6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:center-focus-strong" /></template>

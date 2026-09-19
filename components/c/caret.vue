<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry3wv0bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ry3wv0bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:caret" /></template>

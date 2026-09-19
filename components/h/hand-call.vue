<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6q3vijat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="l6q3vijat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-call" /></template>

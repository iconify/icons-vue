<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rozeiqona.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rozeiqona"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:border-all" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz48f76fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="fz48f76fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-duo" /></template>

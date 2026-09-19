<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jya-soblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="jya-soblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-line-end-duo" /></template>

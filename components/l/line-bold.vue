<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahorj_tjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ahorj_tjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:line-bold" /></template>

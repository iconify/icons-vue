<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3hh6zbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="a3hh6zbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:link-duo" /></template>

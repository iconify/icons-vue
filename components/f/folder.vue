<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2cn-0pih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="u2cn-0pih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:folder" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/non__abbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="non__abbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:celsius" /></template>

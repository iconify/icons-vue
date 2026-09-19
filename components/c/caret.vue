<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er3n1379x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="er3n1379x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:caret" /></template>

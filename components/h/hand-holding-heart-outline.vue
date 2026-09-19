<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk7d680ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pk7d680ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-holding-heart-outline" /></template>

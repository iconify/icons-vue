<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by65-jbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="by65-jbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:helicopter" /></template>

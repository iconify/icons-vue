<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uti_wsw4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="uti_wsw4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:landmark-1-outline" /></template>

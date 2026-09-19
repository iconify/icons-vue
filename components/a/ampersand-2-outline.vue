<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxj1znb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pxj1znb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ampersand-2-outline" /></template>

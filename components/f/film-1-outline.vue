<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tenpnlz4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tenpnlz4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:film-1-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiu0-hwpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="uiu0-hwpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:credit-card-front-bold" /></template>

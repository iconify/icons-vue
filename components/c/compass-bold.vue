<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-g_txqbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="v-g_txqbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:compass-bold" /></template>

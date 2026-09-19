<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2pjovc9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l2pjovc9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:kiss-bold" /></template>

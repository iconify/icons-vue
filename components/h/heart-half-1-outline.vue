<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwor0sbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nwor0sbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-half-1-outline" /></template>

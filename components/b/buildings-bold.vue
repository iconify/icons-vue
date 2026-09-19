<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r694sh4sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r694sh4sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:buildings-bold" /></template>

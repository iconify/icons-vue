<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndna15brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ndna15brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chart-line-outline" /></template>

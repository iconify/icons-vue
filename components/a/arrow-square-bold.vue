<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzvfc_bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bzvfc_bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-square-bold" /></template>

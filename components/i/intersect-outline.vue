<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5uo-2b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l5uo-2b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:intersect-outline" /></template>

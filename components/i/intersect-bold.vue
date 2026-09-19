<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hafyv4dci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hafyv4dci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:intersect-bold" /></template>

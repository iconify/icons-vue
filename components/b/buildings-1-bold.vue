<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfy0pmjmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tfy0pmjmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:buildings-1-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe09umb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="fe09umb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bars-offset-1-bold" /></template>

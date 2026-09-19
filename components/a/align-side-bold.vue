<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w84gz-b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="w84gz-b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-side-bold" /></template>

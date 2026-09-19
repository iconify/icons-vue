<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp29a1_7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wp29a1_7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:head-side-bold" /></template>

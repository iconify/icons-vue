<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3gyce2qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="u3gyce2qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:border-all" /></template>

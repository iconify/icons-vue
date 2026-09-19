<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-b327y9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="s-b327y9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layer-foward-outline" /></template>

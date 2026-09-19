<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7qq7q29t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="i7qq7q29t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bells-outline" /></template>

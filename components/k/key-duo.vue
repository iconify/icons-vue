<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny13rhbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ny13rhbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:key-duo" /></template>

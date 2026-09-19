<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4723bcit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="i4723bcit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bike-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt9d2mb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vt9d2mb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cog-duo" /></template>

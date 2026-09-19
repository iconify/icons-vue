<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm2av2mxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zm2av2mxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:life-ring-bold" /></template>

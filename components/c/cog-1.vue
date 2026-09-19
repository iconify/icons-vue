<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a088n9bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a088n9bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:cog-1" /></template>

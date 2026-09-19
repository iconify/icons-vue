<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2bwcfkbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="u2bwcfkbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bandage-1-outline" /></template>

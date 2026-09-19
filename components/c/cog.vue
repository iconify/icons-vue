<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1zrh8b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c1zrh8b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:cog" /></template>

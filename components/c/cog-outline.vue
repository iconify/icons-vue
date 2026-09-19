<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zvk8vqbhu.css';
import '../../css/t/tqg5t2iuz.css';
import '../../css/r/rs4b7ub-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="zvk8vqbhu"/><path clip-rule="evenodd" class="tqg5t2iuz"/><path class="rs4b7ub-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:cog-outline" /></template>

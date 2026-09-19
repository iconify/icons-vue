<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kde8uybpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="kde8uybpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:e-bold" /></template>

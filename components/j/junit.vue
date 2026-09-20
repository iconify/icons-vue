<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i242pgvho.css';
import '../../css/i/ijptld2hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="i242pgvho"/><path class="ijptld2hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:junit" /></template>

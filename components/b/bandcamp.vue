<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-9z9ps0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f-9z9ps0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:bandcamp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km523rbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="km523rbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-level-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw6efdbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mw6efdbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:border-all-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyvjlmb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fyvjlmb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:kick-scooter-outline" /></template>

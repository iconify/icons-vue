<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo8l09wir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wo8l09wir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ear-duo" /></template>

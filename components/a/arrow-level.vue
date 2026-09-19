<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9q9quzbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="d9q9quzbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-level" /></template>

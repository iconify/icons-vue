<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw0lrnb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="vw0lrnb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:analytics" /></template>

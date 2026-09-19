<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghp_0ac9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ghp_0ac9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:i" /></template>

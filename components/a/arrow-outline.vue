<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3g1x1bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="b3g1x1bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-outline" /></template>

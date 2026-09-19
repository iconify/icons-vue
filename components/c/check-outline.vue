<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stpoqex2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="stpoqex2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:check-outline" /></template>

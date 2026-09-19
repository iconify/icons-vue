<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dccqqjb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dccqqjb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:baseball-bat-outline" /></template>

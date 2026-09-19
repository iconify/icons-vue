<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2357wbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s2357wbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bolt-1-duo" /></template>

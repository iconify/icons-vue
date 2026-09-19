<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vod-ixb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vod-ixb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:h-2-outline" /></template>

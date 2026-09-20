<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rss1k6blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rss1k6blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fuga-cloud" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9yt1cc9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="m9yt1cc9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:folder-open-1-outline" /></template>

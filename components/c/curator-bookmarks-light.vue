<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5h_zua9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p5h_zua9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:curator-bookmarks-light" /></template>

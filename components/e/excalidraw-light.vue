<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnmr5yb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fnmr5yb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:excalidraw-light" /></template>

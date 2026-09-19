<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvc3xoy3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nvc3xoy3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-triangle-outline" /></template>

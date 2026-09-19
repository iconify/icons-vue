<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojzurcvfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ojzurcvfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:handshake-outline" /></template>

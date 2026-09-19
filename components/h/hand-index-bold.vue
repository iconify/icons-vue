<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm9kbmb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fm9kbmb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-index-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9pw1tb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="p9pw1tb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:elevator-bold" /></template>

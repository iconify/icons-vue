<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvpz3_mij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bvpz3_mij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:hand-call" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv-kahgmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fv-kahgmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:life-ring-outline" /></template>

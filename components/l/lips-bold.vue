<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv6bx_bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="sv6bx_bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:lips-bold" /></template>

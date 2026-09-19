<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wynr2uy_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wynr2uy_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-stand-west-outline" /></template>

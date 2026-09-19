<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3vxv7txk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z3vxv7txk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:camp-outline" /></template>

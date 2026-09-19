<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epi5pwbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="epi5pwbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:caret-square-bold" /></template>

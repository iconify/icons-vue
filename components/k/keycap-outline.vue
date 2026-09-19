<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqi1sbb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="eqi1sbb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:keycap-outline" /></template>

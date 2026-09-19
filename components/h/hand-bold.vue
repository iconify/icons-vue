<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq658992j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bq658992j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hand-bold" /></template>

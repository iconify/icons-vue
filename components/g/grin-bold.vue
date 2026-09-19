<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wchwsk_5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wchwsk_5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grin-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu_lq32wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tu_lq32wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:add-document-note" /></template>

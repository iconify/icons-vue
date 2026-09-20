<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgt_iob2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xgt_iob2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jupyter-dark" /></template>

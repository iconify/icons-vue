<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub6p_vdiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="ub6p_vdiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:hdr-strong" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbr2puogx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="xbr2puogx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:fullscreen" /></template>

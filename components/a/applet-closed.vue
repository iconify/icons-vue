<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq7uf_biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xq7uf_biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:applet-closed" /></template>

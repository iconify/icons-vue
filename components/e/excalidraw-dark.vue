<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj38i35vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xj38i35vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:excalidraw-dark" /></template>

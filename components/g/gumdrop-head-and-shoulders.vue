<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz7p0yhdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pz7p0yhdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gumdrop-head-and-shoulders" /></template>

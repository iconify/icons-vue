<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taqcn9bfg.css';
import '../../css/b/bbny_5ghg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="taqcn9bfg"/><path class="bbny_5ghg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eonvelope-dark" /></template>

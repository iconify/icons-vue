<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u767w3b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u767w3b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-chrome-dark" /></template>

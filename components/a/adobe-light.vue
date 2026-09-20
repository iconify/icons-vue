<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1h2zlbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y1h2zlbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-light" /></template>

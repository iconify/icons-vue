<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frl-pebdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="frl-pebdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ipvanish-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vblbdac_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vblbdac_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:block-seven" /></template>

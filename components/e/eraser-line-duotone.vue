<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xmnsxcc-k.css';
import '../../css/t/tqdmbdbhu.css';
import '../../css/o/od5ylubiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xmnsxcc-k"/><path class="tqdmbdbhu"/><path class="od5ylubiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eraser-line-duotone" /></template>

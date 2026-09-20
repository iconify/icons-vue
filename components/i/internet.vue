<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g_m248b8z.css';
import '../../css/t/tely9lb-g.css';
import '../../css/y/y4yl88bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g_m248b8z"/><path clip-rule="evenodd" class="tely9lb-g"/><path class="y4yl88bpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:internet" /></template>

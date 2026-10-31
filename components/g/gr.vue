<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/p8eiwgunm.css';
import '../../css/n/nn4h-1bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":301,"height":201};
const content = `<g class="bi12bsetm"><path class="p8eiwgunm"/><path class="nn4h-1bks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:gr" /></template>

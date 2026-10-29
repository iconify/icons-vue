<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v3xxggbuv.css';
import '../../css/f/fngyexhig.css';
import '../../css/d/d6r7_2bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v3xxggbuv"/><path class="fngyexhig wm-k"/><path class="d6r7_2bbn wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-filter-sketch" /></template>

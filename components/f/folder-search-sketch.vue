<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/ra7gopb2d.css';
import '../../css/t/tfkrzecse.css';
import '../../css/r/rb4930b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ra7gopb2d"/><path class="tfkrzecse wm-k"/><path class="rb4930b7e wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:folder-search-sketch" /></template>

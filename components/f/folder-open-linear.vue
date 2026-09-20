<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/svw4_lb5n.css';
import '../../css/n/n6kdhccvk.css';
import '../../css/o/o4he8kb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="svw4_lb5n"/><path class="n6kdhccvk"/><path class="o4he8kb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-open-linear" /></template>

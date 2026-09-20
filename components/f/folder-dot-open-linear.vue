<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/svw4_lb5n.css';
import '../../css/o/o4he8kb_o.css';
import '../../css/z/zn-yurbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="svw4_lb5n"/><path class="o4he8kb_o"/><path class="zn-yurbog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-dot-open-linear" /></template>

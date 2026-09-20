<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/djw9-2b1i.css';
import '../../css/s/sp7l-g4-y.css';
import '../../css/o/o4he8kb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="djw9-2b1i"/><path class="sp7l-g4-y"/><path class="o4he8kb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-open-line-duotone" /></template>

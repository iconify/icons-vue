<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u7rnc-b2i.css';
import '../../css/l/l_ozfcb5g.css';
import '../../css/h/htyeo47eu.css';
import '../../css/n/n97t2jq8e.css';
import '../../css/w/wb3xeub9v.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="u7rnc-b2i"/><path clip-rule="evenodd" class="l_ozfcb5g"/><path clip-rule="evenodd" class="htyeo47eu"/><path clip-rule="evenodd" class="n97t2jq8e"/><path clip-rule="evenodd" class="wb3xeub9v"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:down-up-off" /></template>

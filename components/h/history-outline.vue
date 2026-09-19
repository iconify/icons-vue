<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/ef8pwpb6n.css';
import '../../css/s/sleouwb3s.css';
import '../../css/w/w-asugb8r.css';
import '../../css/e/elikaogpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ef8pwpb6n"/><path class="sleouwb3s"/><path class="w-asugb8r"/><path class="elikaogpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:history-outline" /></template>

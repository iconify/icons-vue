<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c5szvdnvs.css';
import '../../css/d/ddymbxshg.css';
import '../../css/n/nwj63hb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="c5szvdnvs"/><path class="ddymbxshg"/><path class="nwj63hb-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:edit-outline" /></template>

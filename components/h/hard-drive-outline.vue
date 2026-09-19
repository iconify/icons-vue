<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ytwk7rbeg.css';
import '../../css/e/evok60j1h.css';
import '../../css/t/th2sp9bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ytwk7rbeg"/><path clip-rule="evenodd" class="evok60j1h"/><path class="th2sp9bkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hard-drive-outline" /></template>

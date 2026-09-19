<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/m/my50xkbpo.css';
import '../../css/p/pnx-zac0m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4DtUacSN"><g class="v3_i3wktz"><path class="my50xkbpo"/><path class="pnx-zac0m"/></g></mask></defs><path mask="url(#SVG4DtUacSN)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-excel" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/ft06h7b8o.css';
import '../../css/p/peznpibsk.css';
import '../../css/i/itmriibio.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcRUh3dAZ"><g class="ft5dv1b6b"><path class="ft06h7b8o"/><path class="peznpibsk"/><path class="itmriibio"/></g></mask></defs><path mask="url(#SVGcRUh3dAZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:hotel-please-clean" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/x/xwsdf1-vt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnPr2Qbgk"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="xwsdf1-vt"/></g></mask></defs><path mask="url(#SVGnPr2Qbgk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:arrow-circle-down" /></template>

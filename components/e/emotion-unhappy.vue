<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/m/mir4otbpn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDocJv2Rk"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="mir4otbpn"/></g></mask></defs><path mask="url(#SVGDocJv2Rk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:emotion-unhappy" /></template>

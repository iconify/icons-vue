<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/u/u6df5xh0x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaHcRUcLK"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="u6df5xh0x"/></g></mask></defs><path mask="url(#SVGaHcRUcLK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:frowning-face-whit-open-mouth" /></template>

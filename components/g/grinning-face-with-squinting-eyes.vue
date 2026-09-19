<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/n/ncnv649nf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRwe1BbPC"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="ncnv649nf"/></g></mask></defs><path mask="url(#SVGRwe1BbPC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:grinning-face-with-squinting-eyes" /></template>

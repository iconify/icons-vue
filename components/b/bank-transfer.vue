<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/j/jz--rmbcb.css';
import '../../css/m/mvadfabkx.css';
import '../../css/l/lq3-qpbeu.css';
import '../../css/m/m8de0q6nv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRYblmcyU"><g class="ufeehvblu"><rect class="jz--rmbcb"/><path class="mvadfabkx"/><path class="lq3-qpbeu"/><path class="m8de0q6nv"/></g></mask></defs><path mask="url(#SVGRYblmcyU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bank-transfer" /></template>

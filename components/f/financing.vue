<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/i/ix6japbud.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMOIx6bCt"><g class="ufeehvblu"><path class="oo_vs07_g"/><rect transform="rotate(45 24 16.929)" class="ix6japbud"/></g></mask></defs><path mask="url(#SVGMOIx6bCt)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:financing" /></template>

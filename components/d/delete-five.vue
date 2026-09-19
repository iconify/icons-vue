<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/s/s-kistkta.css';
import '../../css/u/u-8_srfhg.css';
import '../../css/h/hv9f26_mj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXL1SydBb"><g class="ufeehvblu"><path class="s-kistkta"/><path class="u-8_srfhg"/><path class="hv9f26_mj"/></g></mask></defs><path mask="url(#SVGXL1SydBb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:delete-five" /></template>

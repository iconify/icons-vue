<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n_fh5517m.css';
import '../../css/n/ncnkpacjq.css';
import '../../css/f/fcdvm57xw.css';
import '../../css/s/s215cnbbv.css';
import '../../css/k/kkjyhz4us.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpFntBcaT"><g class="ft5dv1b6b"><path class="n_fh5517m"/><circle class="ncnkpacjq"/><circle class="fcdvm57xw"/><circle class="s215cnbbv"/><circle class="kkjyhz4us"/></g></mask></defs><path mask="url(#SVGpFntBcaT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:frog" /></template>

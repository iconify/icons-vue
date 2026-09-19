<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/c/cu5xsb1ef.css';
import '../../css/y/yt7696q7d.css';
import '../../css/g/gcdut9pir.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTrxrfcnb"><g class="hv130ab-t"><rect class="cu5xsb1ef"/><path class="yt7696q7d"/><path class="gcdut9pir"/></g></mask></defs><path mask="url(#SVGTrxrfcnb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:ethernet-on" /></template>

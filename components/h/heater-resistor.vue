<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/a/ah54-cccv.css';
import '../../css/c/cyf0llfok.css';
import '../../css/z/zxhwh9mgr.css';
import '../../css/u/uu8-2gbpn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgmrblevU"><g class="ufeehvblu"><rect transform="rotate(-45 9.858 29.657)" class="ah54-cccv"/><path class="cyf0llfok"/><path class="zxhwh9mgr"/><path class="uu8-2gbpn"/></g></mask></defs><path mask="url(#SVGgmrblevU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:heater-resistor" /></template>

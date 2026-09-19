<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/wr9hafbnl.css';
import '../../css/r/rjaer0dlx.css';
import '../../css/f/f8pnpzbfo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHl06vcSf"><g class="ufeehvblu"><path class="wr9hafbnl"/><path class="rjaer0dlx"/><path class="f8pnpzbfo"/></g></mask></defs><path mask="url(#SVGHl06vcSf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:calculator" /></template>

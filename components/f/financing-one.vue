<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/n/ne-y4bcan.css';
import '../../css/v/vnrhmrbcz.css';
import '../../css/c/c4w93dekp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGF704Bdhr"><g class="ufeehvblu"><path class="ne-y4bcan"/><path class="vnrhmrbcz"/><path clip-rule="evenodd" class="c4w93dekp"/></g></mask></defs><path mask="url(#SVGF704Bdhr)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:financing-one" /></template>

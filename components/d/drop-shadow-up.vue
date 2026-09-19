<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/u/ulte-guim.css';
import '../../css/k/kwzrzeqtd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhGQmxeQo"><g class="hv130ab-t"><path clip-rule="evenodd" class="ulte-guim"/><path class="kwzrzeqtd"/></g></mask></defs><path mask="url(#SVGhGQmxeQo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:drop-shadow-up" /></template>

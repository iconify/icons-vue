<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/x/x44bfmbwq.css';
import '../../css/o/ohqv07ktw.css';
import '../../css/r/rbw0mx1jr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhfz8cZWl"><g class="ufeehvblu"><path class="x44bfmbwq"/><path class="ohqv07ktw"/><path class="rbw0mx1jr"/></g></mask></defs><path mask="url(#SVGhfz8cZWl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:aperture-priority" /></template>

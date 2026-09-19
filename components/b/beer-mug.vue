<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/b/bd8ephb8q.css';
import '../../css/g/gwpoo533p.css';
import '../../css/u/u65--k4ig.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGks21oeDl"><g class="ufeehvblu"><path class="bd8ephb8q"/><path class="gwpoo533p"/><path class="u65--k4ig"/></g></mask></defs><path mask="url(#SVGks21oeDl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:beer-mug" /></template>

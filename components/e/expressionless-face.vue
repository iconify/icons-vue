<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/c/c6j5yyb2e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGil5VI8zv"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="c6j5yyb2e"/></g></mask></defs><path mask="url(#SVGil5VI8zv)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:expressionless-face" /></template>

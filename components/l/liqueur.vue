<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/l/lf1jqulvz.css';
import '../../css/b/bjs1snb0u.css';
import '../../css/g/g92hyzclq.css';
import '../../css/h/h2x_h3b3t.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkcF3kcNk"><g class="hv130ab-t"><path class="lf1jqulvz"/><path class="bjs1snb0u"/><path class="g92hyzclq"/><path class="h2x_h3b3t"/></g></mask></defs><path mask="url(#SVGkcF3kcNk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:liqueur" /></template>

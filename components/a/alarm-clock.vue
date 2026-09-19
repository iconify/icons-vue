<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/c/c6jtjthhk.css';
import '../../css/f/fcu8rib6g.css';
import '../../css/n/ntbo-qb0z.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzvT79cfR"><g class="ufeehvblu"><path class="c6jtjthhk"/><path class="fcu8rib6g"/><path class="ntbo-qb0z"/></g></mask></defs><path mask="url(#SVGzvT79cfR)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:alarm-clock" /></template>

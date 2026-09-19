<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/f/fgokb7h8d.css';
import '../../css/z/zw-68k1ry.css';
import '../../css/z/z2hbabcdb.css';
import '../../css/a/al3gikwgt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYReMxexd"><g class="ufeehvblu"><path class="fgokb7h8d"/><rect class="zw-68k1ry"/><rect class="z2hbabcdb"/><path class="al3gikwgt"/></g></mask></defs><path mask="url(#SVGYReMxexd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:city-one" /></template>

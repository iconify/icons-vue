<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/j/jh506iphg.css';
import '../../css/c/cz-xh6lnw.css';
import '../../css/c/c9e4w6bhq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBeBcAesw"><g class="hv130ab-t"><path class="jh506iphg"/><path class="cz-xh6lnw"/><path class="c9e4w6bhq"/></g></mask></defs><path mask="url(#SVGBeBcAesw)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:lip-gloss" /></template>

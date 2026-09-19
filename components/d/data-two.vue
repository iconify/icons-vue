<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/q97o_r-5j.css';
import '../../css/f/fut_hknti.css';
import '../../css/v/vf4h32bmh.css';
import '../../css/i/ib2bsphlp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaDEdsb6M"><g class="aql7dnt-u"><ellipse class="q97o_r-5j"/><path class="fut_hknti"/><path class="vf4h32bmh"/><path class="ib2bsphlp"/></g></mask></defs><path mask="url(#SVGaDEdsb6M)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:data-two" /></template>

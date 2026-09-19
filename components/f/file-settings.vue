<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rohhhzb0l.css';
import '../../css/f/fvtb_21_v.css';
import '../../css/w/wht39nbrx.css';
import '../../css/r/ruo6wwnlr.css';
import '../../css/m/m1mo2dbtk.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOGZkoc9i"><g class="rohhhzb0l"><path class="fvtb_21_v"/><path class="wht39nbrx"/><circle class="ruo6wwnlr"/><path class="m1mo2dbtk"/></g></mask></defs><path mask="url(#SVGOGZkoc9i)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-settings" /></template>

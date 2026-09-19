<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_swcb_o.css';
import '../../css/h/hf-3oib-y.css';
import '../../css/t/tmpm_6byj.css';
import '../../css/h/h9t6l4bmz.css';
import '../../css/p/pb7vd9b3l.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPGl8Mcah"><g class="v1_swcb_o"><path class="hf-3oib-y"/><circle class="tmpm_6byj"/><circle class="h9t6l4bmz"/><circle class="pb7vd9b3l"/></g></mask></defs><path mask="url(#SVGPGl8Mcah)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:list-one" /></template>

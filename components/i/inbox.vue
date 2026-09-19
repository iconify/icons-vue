<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/x_ct48b7d.css';
import '../../css/x/xt05grelv.css';
import '../../css/j/jqna_5nqw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTAqdHcnF"><g class="v3_i3wktz"><path class="x_ct48b7d"/><path class="xt05grelv"/><path class="jqna_5nqw"/></g></mask></defs><path mask="url(#SVGTAqdHcnF)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:inbox" /></template>

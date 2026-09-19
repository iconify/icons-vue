<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/r_6nlzbtv.css';
import '../../css/l/l-hm_u4_z.css';
import '../../css/a/appofdctq.css';
import '../../css/q/qig_zznph.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOR8ep13r"><g class="v3_i3wktz"><path class="r_6nlzbtv"/><path class="l-hm_u4_z"/><path class="appofdctq"/><path class="qig_zznph"/></g></mask></defs><path mask="url(#SVGOR8ep13r)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bus" /></template>

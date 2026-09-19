<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_swcb_o.css';
import '../../css/w/wcezl0bkc.css';
import '../../css/p/pn48gtbgw.css';
import '../../css/w/wiuhzdagt.css';
import '../../css/u/uj0e2ibws.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGj87WgcUk"><g class="v1_swcb_o"><path class="wcezl0bkc"/><circle class="pn48gtbgw"/><circle class="wiuhzdagt"/><circle class="uj0e2ibws"/></g></mask></defs><path mask="url(#SVGj87WgcUk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:crown-three" /></template>

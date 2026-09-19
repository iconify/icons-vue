<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/l/lrhbazbif.css';
import '../../css/q/qjunyybpn.css';
import '../../css/j/jq3ltpbcw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEGHG9w6m"><g class="hv130ab-t"><path class="lrhbazbif"/><path class="qjunyybpn"/><path class="jq3ltpbcw"/></g></mask></defs><path mask="url(#SVGEGHG9w6m)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hot-pot-one" /></template>

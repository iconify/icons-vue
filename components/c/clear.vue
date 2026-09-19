<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/n24zlup5f.css';
import '../../css/v/vhduzt6mh.css';
import '../../css/x/xbne_mbps.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKuwQcmRM"><g class="v3_i3wktz"><path clip-rule="evenodd" class="n24zlup5f"/><path class="vhduzt6mh"/><path class="xbne_mbps"/></g></mask></defs><path mask="url(#SVGKuwQcmRM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:clear" /></template>

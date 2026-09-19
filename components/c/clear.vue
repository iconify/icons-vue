<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/y/yt2phnb2o.css';
import '../../css/a/ap86pbbgg.css';
import '../../css/z/zp5xfc9ub.css';
import '../../css/z/zgvicp2_u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGy5LHldBK"><g class="ufeehvblu"><path clip-rule="evenodd" class="yt2phnb2o"/><path class="ap86pbbgg"/><path class="zp5xfc9ub"/><path class="zgvicp2_u"/></g></mask></defs><path mask="url(#SVGy5LHldBK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:clear" /></template>

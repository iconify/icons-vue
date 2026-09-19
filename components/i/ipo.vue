<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oh_e7zb2w.css';
import '../../css/w/wdi0syhdo.css';
import '../../css/u/ul5gnlx5m.css';
import '../../css/q/qodtiuben.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRkQAljxN"><g class="ufeehvblu"><path class="oh_e7zb2w"/><path class="wdi0syhdo"/><path class="ul5gnlx5m"/><ellipse class="qodtiuben"/></g></mask></defs><path mask="url(#SVGRkQAljxN)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:ipo" /></template>

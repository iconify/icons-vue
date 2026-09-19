<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/y/ys67npbsn.css';
import '../../css/x/xfswdop-m.css';
import '../../css/x/xtbnnobia.css';
import '../../css/n/nzuotib9e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRBQrpehk"><g class="s9cl3zbei"><path class="ys67npbsn"/><path class="xfswdop-m"/><path class="xtbnnobia"/><path class="nzuotib9e"/></g></mask></defs><path mask="url(#SVGRBQrpehk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:baggage-delay" /></template>

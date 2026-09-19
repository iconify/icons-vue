<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/w/ws_yc2k8c.css';
import '../../css/o/o6az9xqfd.css';
import '../../css/i/icy9jdz7f.css';
import '../../css/s/sbh5_5buf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFFdJMd2U"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="ws_yc2k8c"/><path class="o6az9xqfd"/><path class="icy9jdz7f"/><path class="sbh5_5buf"/></g></mask></defs><path mask="url(#SVGFFdJMd2U)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:layout-five" /></template>

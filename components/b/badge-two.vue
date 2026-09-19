<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/l/lyvb5g3tc.css';
import '../../css/p/p4hvhac_x.css';
import '../../css/o/o6lexionm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPF5ztdPr"><g class="wwvp95byt"><path class="lyvb5g3tc"/><path class="p4hvhac_x"/><path class="o6lexionm"/></g></mask></defs><path mask="url(#SVGPF5ztdPr)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:badge-two" /></template>

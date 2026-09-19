<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/w/whph_o--x.css';
import '../../css/q/qdjay_j5b.css';
import '../../css/y/yveo74b2b.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWNgSieUZ"><g class="ufeehvblu"><path class="whph_o--x"/><path class="qdjay_j5b"/><path class="yveo74b2b"/></g></mask></defs><path mask="url(#SVGWNgSieUZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:install" /></template>

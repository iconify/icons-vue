<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/gj7mgbb6o.css';
import '../../css/d/dwjj-xavx.css';
import '../../css/n/nhqcy2b9w.css';
import '../../css/v/vujj_bc1c.css';
import '../../css/x/xjfnb9n4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="gj7mgbb6o"/><path class="dwjj-xavx"/><path class="nhqcy2b9w"/><path class="vujj_bc1c"/><path class="xjfnb9n4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:exchange-three" /></template>

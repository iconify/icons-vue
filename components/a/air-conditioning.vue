<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/i/ifxv5jnsx.css';
import '../../css/r/rk-tksbzu.css';
import '../../css/s/s91atubcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="ifxv5jnsx"/><path class="rk-tksbzu"/><path class="s91atubcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:air-conditioning" /></template>

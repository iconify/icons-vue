<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zen2agbyu.css';
import '../../css/t/ty9mbj_-y.css';
import '../../css/m/me9i_ernp.css';
import '../../css/t/t5pe0rbpg.css';
import '../../css/h/hxd-si7bb.css';
import '../../css/s/s426uxbfb.css';
import '../../css/t/t3xbxgbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zen2agbyu"/><path class="ty9mbj_-y"/><path class="me9i_ernp"/><path class="t5pe0rbpg"/><path class="hxd-si7bb"/><path class="s426uxbfb"/><path class="t3xbxgbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:aperture-48" /></template>

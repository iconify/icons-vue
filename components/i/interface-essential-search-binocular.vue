<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz_z2dbnt.css';
import '../../css/s/swgb96d4x.css';
import '../../css/m/m_yjw2b7s.css';
import '../../css/e/egnlvvb2x.css';
import '../../css/l/lz7k-95pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wz_z2dbnt"/><path class="swgb96d4x"/><path class="m_yjw2b7s"/><path class="egnlvvb2x"/><path class="lz7k-95pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-search-binocular" /></template>

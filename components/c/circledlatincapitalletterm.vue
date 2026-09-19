<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htu5m_cpb.css';
import '../../css/i/iz_fwv24x.css';
import '../../css/u/uwugspbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="htu5m_cpb"/><path class="iz_fwv24x"/><path class="uwugspbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:circledlatincapitalletterm" /></template>

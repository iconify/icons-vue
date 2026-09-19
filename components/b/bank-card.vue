<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/t/tp_-sbc1k.css';
import '../../css/x/x_83sd0yc.css';
import '../../css/v/v1msn87zh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9rsQWPvm"><g class="v3_i3wktz"><path class="tp_-sbc1k"/><path class="x_83sd0yc"/><path class="v1msn87zh"/></g></mask></defs><path mask="url(#SVG9rsQWPvm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bank-card" /></template>

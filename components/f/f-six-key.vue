<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/q/qek2tkbit.css';
import '../../css/h/hgauyrvul.css';
import '../../css/i/i55550s0j.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSrpPkcfM"><g class="s9cl3zbei"><rect class="qek2tkbit"/><path class="hgauyrvul"/><path class="i55550s0j"/></g></mask></defs><path mask="url(#SVGSrpPkcfM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:f-six-key" /></template>

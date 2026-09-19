<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mqx9rpnoy.css';
import '../../css/t/txn-vvbbr.css';
import '../../css/d/d21rknbda.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGX9qUOAmp"><g class="ft5dv1b6b"><path class="mqx9rpnoy"/><path clip-rule="evenodd" class="txn-vvbbr"/><path class="d21rknbda"/></g></mask></defs><path mask="url(#SVGX9qUOAmp)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:info" /></template>

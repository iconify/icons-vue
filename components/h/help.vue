<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mqx9rpnoy.css';
import '../../css/a/a0ra-m2wj.css';
import '../../css/m/m_uixnbmd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKI5kpbjS"><g class="ft5dv1b6b"><path class="mqx9rpnoy"/><path class="a0ra-m2wj"/><path clip-rule="evenodd" class="m_uixnbmd"/></g></mask></defs><path mask="url(#SVGKI5kpbjS)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:help" /></template>

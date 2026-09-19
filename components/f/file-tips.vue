<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pc_6km5yf.css';
import '../../css/x/xoyjewber.css';
import '../../css/n/nyo9evb1o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdfYZo3nT"><g class="ft5dv1b6b"><path class="pc_6km5yf"/><path class="xoyjewber"/><path clip-rule="evenodd" class="nyo9evb1o"/></g></mask></defs><path mask="url(#SVGdfYZo3nT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-tips" /></template>

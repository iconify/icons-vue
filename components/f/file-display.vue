<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pc_6km5yf.css';
import '../../css/f/ff2fwvbbo.css';
import '../../css/d/dxqmg8bmd.css';
import '../../css/p/py6l_fuet.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3PjI2dXl"><g class="ft5dv1b6b"><path class="pc_6km5yf"/><path class="ff2fwvbbo"/><path class="dxqmg8bmd"/><path class="py6l_fuet"/></g></mask></defs><path mask="url(#SVG3PjI2dXl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-display" /></template>

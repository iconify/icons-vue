<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mb02rebgd.css';
import '../../css/i/iy-c-bbdy.css';
import '../../css/c/cm_b0kbjf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGW2nAFbwp"><g class="ft5dv1b6b"><path class="mb02rebgd"/><path class="iy-c-bbdy"/><circle class="cm_b0kbjf"/></g></mask></defs><path mask="url(#SVGW2nAFbwp)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:duck" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/noih5objo.css';
import '../../css/b/buxkfmbco.css';
import '../../css/n/nvkuv6u_b.css';
import '../../css/d/dedtfabrl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5jFRBbpO"><g class="ft5dv1b6b"><path class="noih5objo"/><path class="buxkfmbco"/><circle class="nvkuv6u_b"/><circle class="dedtfabrl"/></g></mask></defs><path mask="url(#SVG5jFRBbpO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:android" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/gw-xc6bxf.css';
import '../../css/t/ta1txdbuz.css';
import '../../css/d/d4ec0ab5k.css';
import '../../css/y/ye-rh0b6u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGc2MCbdWa"><g class="v3_i3wktz"><path class="gw-xc6bxf"/><path class="ta1txdbuz"/><path class="d4ec0ab5k"/><path class="ye-rh0b6u"/></g></mask></defs><path mask="url(#SVGc2MCbdWa)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:industrial-scales" /></template>

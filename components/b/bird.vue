<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/isu9bqbpe.css';
import '../../css/x/xwe23ta8r.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGe3smqcPo"><g class="ft5dv1b6b"><path class="isu9bqbpe"/><circle class="xwe23ta8r"/></g></mask></defs><path mask="url(#SVGe3smqcPo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bird" /></template>

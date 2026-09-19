<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rohhhzb0l.css';
import '../../css/f/fvtb_21_v.css';
import '../../css/w/wht39nbrx.css';
import '../../css/m/mze9y3blp.css';
import '../../css/s/sfbrjpc4q.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbASm0cWT"><g class="rohhhzb0l"><path class="fvtb_21_v"/><path class="wht39nbrx"/><circle class="mze9y3blp"/><path class="sfbrjpc4q"/></g></mask></defs><path mask="url(#SVGbASm0cWT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-date" /></template>

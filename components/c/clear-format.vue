<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csw0kbbpv.css';
import '../../css/s/sgw7h0bny.css';
import '../../css/s/sul83f9ve.css';
import '../../css/o/obbrti2nr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAND8ZcBU"><g class="csw0kbbpv"><path class="sgw7h0bny"/><path class="sul83f9ve"/><path class="obbrti2nr"/></g></mask></defs><path mask="url(#SVGAND8ZcBU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:clear-format" /></template>

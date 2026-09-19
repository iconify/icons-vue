<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/p/pz0kzybva.css';
import '../../css/j/juzlxjb7o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGwSbob2g"><g class="v3_i3wktz"><rect class="pz0kzybva"/><path class="juzlxjb7o"/></g></mask></defs><path mask="url(#SVGGwSbob2g)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bank-transfer" /></template>

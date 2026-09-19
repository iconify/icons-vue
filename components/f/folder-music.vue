<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xedzjig2g.css';
import '../../css/u/ud5c6fcjr.css';
import '../../css/o/okqenj9_f.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBtCSXbUx"><g class="v3_i3wktz"><path class="xedzjig2g"/><path class="ud5c6fcjr"/><circle class="okqenj9_f"/></g></mask></defs><path mask="url(#SVGBtCSXbUx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:folder-music" /></template>

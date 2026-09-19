<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/c/cpvlsib2p.css';
import '../../css/a/aa2jaubia.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOftHKdcs"><g class="v3_i3wktz"><path class="cpvlsib2p"/><path class="aa2jaubia"/></g></mask></defs><path mask="url(#SVGOftHKdcs)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-right" /></template>

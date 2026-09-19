<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/avkjhg7eh.css';
import '../../css/a/aeyefqb0j.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGanREEdZE"><g class="v3_i3wktz"><path class="avkjhg7eh"/><path class="aeyefqb0j"/></g></mask></defs><path mask="url(#SVGanREEdZE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:game-ps" /></template>

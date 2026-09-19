<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h4iej7x0c.css';
import '../../css/o/ogc7ubbfh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGXrPvbdT"><g class="v3_i3wktz"><path class="h4iej7x0c"/><path class="ogc7ubbfh"/></g></mask></defs><path mask="url(#SVGGXrPvbdT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:female" /></template>

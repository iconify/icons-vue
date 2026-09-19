<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/e/eh2-i3ale.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8xPXIdjS"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="eh2-i3ale"/></g></mask></defs><path mask="url(#SVG8xPXIdjS)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:loudly-crying-face-whit-open-mouth" /></template>

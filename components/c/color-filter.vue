<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/eum0i25rl.css';
import '../../css/p/p5fn7zxfk.css';
import '../../css/d/db5zhxapf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRa3Mgdns"><g class="v3_i3wktz"><path class="eum0i25rl"/><path class="p5fn7zxfk"/><path class="db5zhxapf"/></g></mask></defs><path mask="url(#SVGRa3Mgdns)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:color-filter" /></template>

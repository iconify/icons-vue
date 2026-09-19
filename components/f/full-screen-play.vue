<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/z/zqp5lnbil.css';
import '../../css/e/e4vcug-lw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGi8dckb7P"><g class="v3_i3wktz"><path class="zqp5lnbil"/><path class="e4vcug-lw"/></g></mask></defs><path mask="url(#SVGi8dckb7P)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:full-screen-play" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/enw8ysjww.css';
import '../../css/a/aou6uxbpc.css';
import '../../css/l/lkb7etlcq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWe0BFeAC"><g class="v3_i3wktz"><path class="enw8ysjww"/><path class="aou6uxbpc"/><path class="lkb7etlcq"/></g></mask></defs><path mask="url(#SVGWe0BFeAC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:connection-point" /></template>

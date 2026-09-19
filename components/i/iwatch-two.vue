<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cor9hjbch.css';
import '../../css/l/lhlk6yb8p.css';
import '../../css/k/kpcmyzith.css';
import '../../css/u/u8nd0acfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="cor9hjbch"/><rect class="lhlk6yb8p"/><rect transform="rotate(90 13 18)" class="kpcmyzith"/><rect transform="rotate(90 13 25)" class="u8nd0acfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:iwatch-two" /></template>

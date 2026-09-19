<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/m/mtr8gtysq.css';
import '../../css/x/x9_-dnb2u.css';
import '../../css/x/xg20wgnod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path clip-rule="evenodd" class="mtr8gtysq"/><path class="x9_-dnb2u"/><path class="xg20wgnod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:download-four" /></template>

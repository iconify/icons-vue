<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/g/gm_y72bsf.css';
import '../../css/w/w3cr9ab-i.css';
import '../../css/j/juw4_ubej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="gm_y72bsf"/><path class="w3cr9ab-i"/><path class="juw4_ubej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:icecream-two" /></template>

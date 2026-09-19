<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/j/j977qfbyx.css';
import '../../css/g/gvqncouol.css';
import '../../css/g/gmlya5hur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="j977qfbyx"/><path class="gvqncouol"/><path class="gmlya5hur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:credit-card-outline" /></template>

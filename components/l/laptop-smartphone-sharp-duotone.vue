<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/h/hlf9xubcs.css';
import '../../css/z/zojokz93c.css';
import '../../css/z/zoch16lok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hlf9xubcs"/><path class="zojokz93c"/><path clip-rule="evenodd" class="zoch16lok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-smartphone-sharp-duotone" /></template>

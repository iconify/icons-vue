<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/a/a8f231k-x.css';
import '../../css/a/ahhqo1b4s.css';
import '../../css/e/ellalvbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a8f231k-x"/><path class="ahhqo1b4s"/><path class="ellalvbgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:link-2-off-sharp-duotone" /></template>

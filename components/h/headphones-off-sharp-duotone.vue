<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/zs8bi0bys.css';
import '../../css/s/sh3xxe9ap.css';
import '../../css/f/f4vx4ccga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zs8bi0bys"/><path class="sh3xxe9ap"/><path class="f4vx4ccga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headphones-off-sharp-duotone" /></template>

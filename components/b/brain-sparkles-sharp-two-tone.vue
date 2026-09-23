<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/w/wwc0abswz.css';
import '../../css/k/ksu4hvb6k.css';
import '../../css/s/saonk0snb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wwc0abswz"/><path class="ksu4hvb6k"/><path class="saonk0snb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:brain-sparkles-sharp-two-tone" /></template>

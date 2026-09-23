<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/m/ma9f4b4xe.css';
import '../../css/n/n26asvj4t.css';
import '../../css/z/z21esqbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ma9f4b4xe"/><path class="n26asvj4t"/><path class="z21esqbjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:battery-sparkles-sharp-two-tone" /></template>

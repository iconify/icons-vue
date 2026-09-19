<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vxbvk3b8j.css';
import '../../css/i/i5thibbft.css';
import '../../css/v/vjqdtotvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vxbvk3b8j"/><path class="i5thibbft"/><path class="vjqdtotvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-axis3d" /></template>

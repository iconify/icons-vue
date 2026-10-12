<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vk43r2bac.css';
import '../../css/g/gis6iufnu.css';
import '../../css/w/w0-ba4bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vk43r2bac"/><path class="gis6iufnu"/><path class="w0-ba4bwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:brush-duotone" /></template>

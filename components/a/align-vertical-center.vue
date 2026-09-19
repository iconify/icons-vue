<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx8y2ds-k.css';
import '../../css/q/q0m24db3d.css';
import '../../css/i/idhaus_4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gx8y2ds-k"><path class="q0m24db3d"/><path class="idhaus_4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:align-vertical-center" /></template>

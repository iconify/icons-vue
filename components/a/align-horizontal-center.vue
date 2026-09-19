<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx8y2ds-k.css';
import '../../css/h/h2-2dgnfu.css';
import '../../css/j/jsmv-tewy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gx8y2ds-k"><path class="h2-2dgnfu"/><path class="jsmv-tewy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:align-horizontal-center" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/g/ggclseb0g.css';
import '../../css/o/of4mc-rsl.css';
import '../../css/f/f-axaw8df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ggclseb0g"/><circle class="of4mc-rsl"/><path class="f-axaw8df"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-co-editing" /></template>

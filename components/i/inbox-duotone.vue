<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uvxfd2b7s.css';
import '../../css/j/jawt2pdal.css';
import '../../css/p/pf5yg-grl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uvxfd2b7s"/><path class="jawt2pdal"/><path class="pf5yg-grl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:inbox-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dm5tfv27h.css';
import '../../css/d/dbq_7acij.css';
import '../../css/x/xxavhac7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dm5tfv27h"/><path class="dbq_7acij"/><path class="xxavhac7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:chart-network-duotone" /></template>

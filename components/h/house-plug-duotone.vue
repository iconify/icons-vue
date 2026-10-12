<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v5tvk7p6f.css';
import '../../css/p/p4xnfxtlo.css';
import '../../css/m/mpi_84bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v5tvk7p6f"/><path class="p4xnfxtlo"/><path class="mpi_84bjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:house-plug-duotone" /></template>

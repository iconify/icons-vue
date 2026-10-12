<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hogx2radb.css';
import '../../css/p/p7si66b8d.css';
import '../../css/l/lobfmib2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hogx2radb"/><path class="p7si66b8d"/><path class="lobfmib2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:coins-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/r0_tkgy3d.css';
import '../../css/u/uelw5zcga.css';
import '../../css/o/obsscdhly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r0_tkgy3d"/><path class="uelw5zcga"/><circle class="obsscdhly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:floppy-disk-2" /></template>

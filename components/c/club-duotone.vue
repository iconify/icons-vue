<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h8s704hzr.css';
import '../../css/a/a_priwvxo.css';
import '../../css/m/mbul8ac9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h8s704hzr"/><path class="a_priwvxo"/><path class="mbul8ac9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:club-duotone" /></template>

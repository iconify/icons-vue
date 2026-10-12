<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/srgpqyrmb.css';
import '../../css/e/ekiupr2qe.css';
import '../../css/b/bet4yfb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="srgpqyrmb"/><path class="ekiupr2qe"/><path class="bet4yfb4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:forklift-duotone" /></template>

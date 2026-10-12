<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uiqpg-b4m.css';
import '../../css/r/rt3fdztit.css';
import '../../css/y/ycnuff8oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uiqpg-b4m"/><path class="rt3fdztit"/><path class="ycnuff8oa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layers-minus-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vez_7om7o.css';
import '../../css/c/cw8ojcn9m.css';
import '../../css/c/cp3a_0dpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vez_7om7o"/><path class="cw8ojcn9m"/><path class="cp3a_0dpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hard-drive-duotone" /></template>

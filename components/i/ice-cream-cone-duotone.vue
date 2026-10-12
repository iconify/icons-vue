<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lagwj0bdl.css';
import '../../css/e/er6snfb-s.css';
import '../../css/o/o5g176b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lagwj0bdl"/><path class="er6snfb-s"/><path class="o5g176b6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ice-cream-cone-duotone" /></template>

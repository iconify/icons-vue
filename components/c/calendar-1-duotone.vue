<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h9wmnt92z.css';
import '../../css/s/s1a2eew1e.css';
import '../../css/p/p3poopb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h9wmnt92z"/><path class="s1a2eew1e"/><path class="p3poopb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-1-duotone" /></template>

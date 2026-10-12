<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vz550iwak.css';
import '../../css/p/p3poopb-f.css';
import '../../css/j/jiqekfbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vz550iwak"/><path class="p3poopb-f"/><path class="jiqekfbcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-cog-duotone" /></template>

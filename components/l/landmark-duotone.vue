<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pnkdaj0ty.css';
import '../../css/s/s25lxsbvo.css';
import '../../css/n/n9nithbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pnkdaj0ty"/><path class="s25lxsbvo"/><path class="n9nithbvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:landmark-duotone" /></template>

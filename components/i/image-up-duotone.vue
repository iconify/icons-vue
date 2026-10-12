<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iyss807dj.css';
import '../../css/c/clm3_tb7h.css';
import '../../css/f/fe81k0bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iyss807dj"/><path class="clm3_tb7h"/><path class="fe81k0bsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:image-up-duotone" /></template>

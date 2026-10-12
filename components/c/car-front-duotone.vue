<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hq5gbsb5w.css';
import '../../css/o/o8drxjbah.css';
import '../../css/r/rmftuj1wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hq5gbsb5w"/><path class="o8drxjbah"/><path class="rmftuj1wn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:car-front-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lsv3emysi.css';
import '../../css/l/lrloqybnl.css';
import '../../css/w/wcftsnbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lsv3emysi"/><path class="lrloqybnl"/><path class="wcftsnbie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber-color:glass-1" /></template>

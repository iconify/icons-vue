<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g2by2f8cm.css';
import '../../css/r/r-lr4020s.css';
import '../../css/o/oochcfc2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g2by2f8cm"/><path class="r-lr4020s"/><path class="oochcfc2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cuboid-duotone" /></template>

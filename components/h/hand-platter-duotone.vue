<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fz9369zld.css';
import '../../css/g/g-zp8bb9f.css';
import '../../css/v/vl2k-fw5k.css';
import '../../css/t/t3p0bzbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fz9369zld"/><path class="g-zp8bb9f"/><path class="vl2k-fw5k"/><path class="t3p0bzbje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-platter-duotone" /></template>

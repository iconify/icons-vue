<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc6w1jbja.css';
import '../../css/k/k0512fcyc.css';
import '../../css/m/m1enbabxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mc6w1jbja"/><path class="k0512fcyc"/><path class="m1enbabxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:command-bold" /></template>

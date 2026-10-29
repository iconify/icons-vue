<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ameo-pbvv.css';
import '../../css/u/ulw-1mb-v.css';
import '../../css/m/mnalv31ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ameo-pbvv"/><path class="ulw-1mb-v wm-a"/><path class="mnalv31ip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:feather-duo" /></template>

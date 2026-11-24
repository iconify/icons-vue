<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wdfqalb9f.css';
import '../../css/u/utvecmj_f.css';
import '../../css/f/fvy498wfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wdfqalb9f"/><path class="utvecmj_f"/><path class="fvy498wfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cigarette-duotone" /></template>

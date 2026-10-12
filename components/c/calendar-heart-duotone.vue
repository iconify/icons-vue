<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pjyby6o7j.css';
import '../../css/p/p3poopb-f.css';
import '../../css/d/d_8ct9emv.css';
import '../../css/v/vv4r3nbqi.css';
import '../../css/u/u72utlerl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pjyby6o7j"/><path class="p3poopb-f"/><path class="d_8ct9emv"/><path class="vv4r3nbqi"/><path class="u72utlerl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-heart-duotone" /></template>

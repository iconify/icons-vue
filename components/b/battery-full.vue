<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nbxszfrsi.css';
import '../../css/m/m1ye8t31x.css';
import '../../css/k/kxw7_zabv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="nbxszfrsi"/><rect class="m1ye8t31x"/><path class="kxw7_zabv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:battery-full" /></template>

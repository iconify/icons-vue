<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pt86bdpnx.css';
import '../../css/r/ryvb81bmv.css';
import '../../css/t/tscubbb5p.css';
import '../../css/e/exzx4mpot.css';
import '../../css/m/m09ioe_cn.css';
import '../../css/z/z8gm7u7km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pt86bdpnx"/><path class="ryvb81bmv"/><path class="tscubbb5p"/><circle class="exzx4mpot"/><circle class="m09ioe_cn"/><circle class="z8gm7u7km"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:flask-light" /></template>

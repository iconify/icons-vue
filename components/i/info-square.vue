<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vv1-bc7dp.css';
import '../../css/h/ho7smwbzh.css';
import '../../css/q/q9mvo8b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vv1-bc7dp"/><path class="ho7smwbzh"/><circle class="q9mvo8b1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:info-square" /></template>

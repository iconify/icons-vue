<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iq2cl0ble.css';
import '../../css/c/cmib70_qd.css';
import '../../css/d/drj4s7sil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iq2cl0ble"/><path clip-rule="evenodd" class="cmib70_qd"/><path class="drj4s7sil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:death-alt-outline-24px" /></template>

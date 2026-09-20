<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h9kcs9b7r.css';
import '../../css/s/sjl_y87kp.css';
import '../../css/n/nv2x_e_ti.css';
import '../../css/y/yi7hai1dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="h9kcs9b7r"/><path clip-rule="evenodd" class="sjl_y87kp"/><path class="nv2x_e_ti"/><path clip-rule="evenodd" class="yi7hai1dr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:handshake" /></template>

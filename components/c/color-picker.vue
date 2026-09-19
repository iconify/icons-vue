<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nxvyzpbvr.css';
import '../../css/s/sl2zlhbqn.css';
import '../../css/o/oc6808bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nxvyzpbvr"/><path class="sl2zlhbqn"/><path class="oc6808bph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:color-picker" /></template>

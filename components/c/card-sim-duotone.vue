<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r6m16c0xn.css';
import '../../css/b/bsldfolwb.css';
import '../../css/x/xoty01rwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="r6m16c0xn"/><path class="bsldfolwb"/><path class="xoty01rwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:card-sim-duotone" /></template>

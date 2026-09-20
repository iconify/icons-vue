<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3xtuk_0z.css';
import '../../css/x/xa_5awkhe.css';
import '../../css/g/gv_l_9bmc.css';
import '../../css/v/vrk4e3cim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="xa_5awkhe"/><path class="gv_l_9bmc"/><path class="vrk4e3cim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:badge-star-2" /></template>

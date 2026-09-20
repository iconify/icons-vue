<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r_l4jyzdi.css';
import '../../css/m/ml556acti.css';
import '../../css/s/s9m_gjbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="r_l4jyzdi"/><path clip-rule="evenodd" class="ml556acti"/><path class="s9m_gjbne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:bell-off" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v4xpcu_js.css';
import '../../css/d/dt5g15b9b.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="v4xpcu_js"/><path clip-rule="evenodd" class="dt5g15b9b"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:flag-off" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/alo-h7bmj.css';
import '../../css/b/bxhrv3bpw.css';
import '../../css/q/q0-dmmbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="alo-h7bmj"/><path clip-rule="evenodd" class="bxhrv3bpw"/><path class="q0-dmmbeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ambulance" /></template>

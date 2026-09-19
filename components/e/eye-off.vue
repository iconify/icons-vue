<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e8f_t6izd.css';
import '../../css/p/pvd6u4yzv.css';
import '../../css/b/b2_d91zpb.css';
import '../../css/c/cn3prr9mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="e8f_t6izd"/><path class="pvd6u4yzv"/><path clip-rule="evenodd" class="b2_d91zpb"/><path class="cn3prr9mx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:eye-off" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn-fd_bpy.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nehzp4d4n.css';
import '../../css/o/o_45fb3ek.css';
import '../../css/g/g9ke79bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bn-fd_bpy"/><g class="cuyn6tgcc"><circle class="nehzp4d4n"/><circle class="o_45fb3ek"/><circle class="g9ke79bbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:list-bullet-fill-16" /></template>

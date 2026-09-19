<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yz2szqn_r.css';
import '../../css/p/p7fmlybcj.css';
import '../../css/o/ouodtacvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="yz2szqn_r"/><path class="p7fmlybcj"/><path clip-rule="evenodd" class="ouodtacvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:dashboard" /></template>

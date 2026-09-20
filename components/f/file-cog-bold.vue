<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fol091bdj.css';
import '../../css/t/t14sqbkgb.css';
import '../../css/c/c73t34bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fol091bdj"/><path clip-rule="evenodd" class="t14sqbkgb"/><path class="c73t34bfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-cog-bold" /></template>

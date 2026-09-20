<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f054vmoxe.css';
import '../../css/v/v6-szcb0s.css';
import '../../css/g/g00mf6bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f054vmoxe"/><path class="v6-szcb0s"/><path clip-rule="evenodd" class="g00mf6bnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clipboard-text-duotone" /></template>

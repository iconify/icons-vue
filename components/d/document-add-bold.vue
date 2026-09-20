<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mwal4cbmx.css';
import '../../css/o/oxqh6ebtn.css';
import '../../css/a/a5daoqjdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mwal4cbmx"/><path class="oxqh6ebtn"/><path class="a5daoqjdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-add-bold" /></template>

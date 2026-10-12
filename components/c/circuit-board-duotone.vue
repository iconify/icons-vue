<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vmhne9bsb.css';
import '../../css/s/s1a2eew1e.css';
import '../../css/t/tkv75thxj.css';
import '../../css/b/betxepw8e.css';
import '../../css/d/ducs5rbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="vmhne9bsb"/><path class="s1a2eew1e"/><path class="tkv75thxj"/><path class="betxepw8e"/><path class="ducs5rbxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circuit-board-duotone" /></template>

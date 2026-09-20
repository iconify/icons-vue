<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pw8owgtbs.css';
import '../../css/t/tvp1jib9y.css';
import '../../css/r/roucdszvd.css';
import '../../css/s/sgw5l6b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="pw8owgtbs"/><path class="tvp1jib9y"/><path class="roucdszvd"/><path class="sgw5l6b8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cd-player-disc" /></template>

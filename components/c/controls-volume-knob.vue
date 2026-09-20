<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/h9o4z3bkr.css';
import '../../css/n/nanjsmb7e.css';
import '../../css/o/oiuzdwzyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="h9o4z3bkr"/><path class="nanjsmb7e"/><path class="oiuzdwzyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:controls-volume-knob" /></template>

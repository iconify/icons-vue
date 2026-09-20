<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gj_2b-kgy.css';
import '../../css/t/t2ojvib5p.css';
import '../../css/m/mup07mi9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gj_2b-kgy"/><path class="t2ojvib5p"/><path class="mup07mi9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:lens-horizontal" /></template>

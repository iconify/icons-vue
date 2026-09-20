<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fdnb98b8v.css';
import '../../css/u/u-m6v9beh.css';
import '../../css/e/ezo8joblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fdnb98b8v"/><path class="u-m6v9beh"/><path class="ezo8joblh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:arduino-plus-minus-1" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x3o7b8xqv.css';
import '../../css/d/duazxfbrd.css';
import '../../css/a/a2zd00mlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x3o7b8xqv"/><path class="duazxfbrd"/><path class="a2zd00mlc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:drawer-download" /></template>

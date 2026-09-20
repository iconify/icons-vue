<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zrg4wdisz.css';
import '../../css/m/mtomw1l9y.css';
import '../../css/n/nsz9pcbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zrg4wdisz"/><path class="mtomw1l9y"/><path class="nsz9pcbni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:color-palette" /></template>

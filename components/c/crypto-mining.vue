<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t08n0l47p.css';
import '../../css/m/mp4y6wb4i.css';
import '../../css/z/zodgzu85w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="t08n0l47p"/><path class="mp4y6wb4i"/><path class="zodgzu85w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:crypto-mining" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbxbaodhg.css';
import '../../css/i/iu6f4fumb.css';
import '../../css/z/zs-5weoak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="vbxbaodhg"><circle class="iu6f4fumb"/><path class="zs-5weoak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:key-duotone-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oasgoj2dk.css';
import '../../css/w/w152snbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="oasgoj2dk"/><path class="w152snbgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:codepen-circle" /></template>

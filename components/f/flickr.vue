<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vti7h_4la.css';
import '../../css/z/znvm40bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-7};
const content = `<g class="cuyn6tgcc"><circle class="vti7h_4la"/><circle class="znvm40bms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:flickr" /></template>

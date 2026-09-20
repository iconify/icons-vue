<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vmd6277yi.css';
import '../../css/l/ld-o23xbi.css';
import '../../css/l/lg0_szb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vmd6277yi"/><path clip-rule="evenodd" class="ld-o23xbi"/><path class="lg0_szb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-codesandbox" /></template>

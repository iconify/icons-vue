<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/u/uiyjj6zbr.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/p/pco18stpg.css';
import '../../css/e/ez41jfban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="uiyjj6zbr wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="pco18stpg"/><path class="ez41jfban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:at-sign-blueprint" /></template>

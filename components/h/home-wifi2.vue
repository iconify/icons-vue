<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f-3v2ab3t.css';
import '../../css/w/wdkrmum0i.css';
import '../../css/e/ewmg-bcus.css';
import '../../css/o/omu5u4v-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f-3v2ab3t"/><path class="wdkrmum0i"/><path class="ewmg-bcus"/><path clip-rule="evenodd" class="omu5u4v-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-wifi2" /></template>

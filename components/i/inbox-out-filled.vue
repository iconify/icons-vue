<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zxjo86bzj.css';
import '../../css/g/gsx79b0zp.css';
import '../../css/c/c2kux8r3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="zxjo86bzj"/><path class="gsx79b0zp"/><path class="c2kux8r3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:inbox-out-filled" /></template>

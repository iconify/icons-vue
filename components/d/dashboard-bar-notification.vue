<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/c/c5kq4ybgs.css';
import '../../css/w/wjp174m-x.css';
import '../../css/d/d9dxm9bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="c5kq4ybgs"/><path class="wjp174m-x"/><path class="d9dxm9bjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-bar-notification" /></template>

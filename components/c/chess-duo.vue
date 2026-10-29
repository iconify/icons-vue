<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gmj017svh.css';
import '../../css/x/xck8kdj3v.css';
import '../../css/p/p81j7dbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gmj017svh"/><path class="wm-a xck8kdj3v"/><path class="p81j7dbae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chess-duo" /></template>

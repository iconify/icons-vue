<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wowg0tbut.css';
import '../../css/k/kqt1ogbeo.css';
import '../../css/h/h0-ybdbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wowg0tbut"/><path class="kqt1ogbeo"/><path class="h0-ybdbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:design-process-mouse-pen" /></template>

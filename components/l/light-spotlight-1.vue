<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hajiifygo.css';
import '../../css/a/a185onbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hajiifygo"/><path class="a185onbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:light-spotlight-1" /></template>

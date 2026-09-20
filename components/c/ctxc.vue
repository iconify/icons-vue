<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5tm16s_g.css';
import '../../css/r/rj75uw35p.css';
import '../../css/h/h5s278hih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5tm16s_g"/><path class="rj75uw35p"/><path class="h5s278hih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ctxc" /></template>

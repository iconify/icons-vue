<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1_erobys.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/spokbjbne.css';
import '../../css/f/f8xqsfb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1_erobys secondary"/><g class="dt0cm9dhy primary"><path class="spokbjbne"/><path class="f8xqsfb6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:compass-duo" /></template>

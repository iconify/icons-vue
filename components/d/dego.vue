<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku5-asgud.css';
import '../../css/h/hy5jsbbuj.css';
import '../../css/t/t32f0z35j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku5-asgud"/><path class="hy5jsbbuj"/><path class="t32f0z35j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dego" /></template>

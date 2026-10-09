<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxllr2mpy.css';
import '../../css/q/q3acjfbyd.css';
import '../../css/k/kzer2rmvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qxllr2mpy"/><path class="q3acjfbyd"/><path class="kzer2rmvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flange-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2vpa7-wx.css';
import '../../css/a/aytccm9qb.css';
import '../../css/l/lqxjulbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h2vpa7-wx"/><path class="aytccm9qb"/><path class="lqxjulbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:camera-reverse-outline" /></template>

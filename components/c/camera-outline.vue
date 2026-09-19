<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2vpa7-wx.css';
import '../../css/q/q_r9obkld.css';
import '../../css/f/fnfrkrn2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h2vpa7-wx"/><circle class="q_r9obkld"/><path class="fnfrkrn2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:camera-outline" /></template>

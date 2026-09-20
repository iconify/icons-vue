<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilfwspl_f.css';
import '../../css/c/cvojyd_oj.css';
import '../../css/j/jlkzze14k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ilfwspl_f"/><path class="cvojyd_oj"/><path class="jlkzze14k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glances" /></template>

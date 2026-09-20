<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrbyzachg.css';
import '../../css/p/p5hooobjg.css';
import '../../css/l/lz3_q5bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrbyzachg"/><path class="p5hooobjg"/><path class="lz3_q5bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-area-multi-filled" /></template>

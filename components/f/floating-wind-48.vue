<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kddy26b4i.css';
import '../../css/y/y5y-mrx_b.css';
import '../../css/j/j5c0g3bgm.css';
import '../../css/o/ok2a0zu8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kddy26b4i"/><path class="y5y-mrx_b"/><path class="j5c0g3bgm"/><path class="ok2a0zu8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:floating-wind-48" /></template>

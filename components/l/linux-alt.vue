<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xstgp02xk.css';
import '../../css/t/tn_hnfb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xstgp02xk"/><path class="tn_hnfb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:linux-alt" /></template>

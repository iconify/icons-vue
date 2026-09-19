<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfp1htbpz.css';
import '../../css/p/p6s0jubwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfp1htbpz"/><path class="p6s0jubwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:background" /></template>

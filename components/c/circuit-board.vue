<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kheaoj4ys.css';
import '../../css/t/t_glypoyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kheaoj4ys"/><path class="t_glypoyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circuit-board" /></template>

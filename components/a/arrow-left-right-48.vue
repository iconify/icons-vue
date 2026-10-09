<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5yx1ibtg.css';
import '../../css/f/fostv5aqj.css';
import '../../css/d/dg_f4ibgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p5yx1ibtg"/><path class="fostv5aqj"/><path class="dg_f4ibgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-left-right-48" /></template>

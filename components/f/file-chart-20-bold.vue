<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8im5qk_h.css';
import '../../css/j/jwtbutb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w8im5qk_h"/><path class="jwtbutb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-chart-20-bold" /></template>

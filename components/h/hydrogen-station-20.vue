<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iixfqsbra.css';
import '../../css/h/h0lo410vx.css';
import '../../css/m/mt37ukw5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iixfqsbra"/><path class="h0lo410vx"/><path class="mt37ukw5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-station-20" /></template>

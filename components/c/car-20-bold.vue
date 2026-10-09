<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxklois4m.css';
import '../../css/t/t_7rprl1m.css';
import '../../css/v/voutigjui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dxklois4m"/><path class="t_7rprl1m"/><path class="voutigjui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:car-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmp_5zpfe.css';
import '../../css/j/jj7ew2vkc.css';
import '../../css/p/pcks-v67p.css';
import '../../css/e/e54bjx_0d.css';
import '../../css/j/jeyqzjnhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fmp_5zpfe"/><path class="jj7ew2vkc"/><path class="pcks-v67p"/><path class="e54bjx_0d"/><path class="jeyqzjnhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-tank-alert-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bji1-u9xf.css';
import '../../css/w/wuqcbyrvq.css';
import '../../css/a/a_99z_b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bji1-u9xf"/><path class="wuqcbyrvq"/><path class="a_99z_b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blade-transport-20" /></template>

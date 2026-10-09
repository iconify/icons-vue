<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et_33pbys.css';
import '../../css/n/n2ffv50qs.css';
import '../../css/p/p2kzhab-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="et_33pbys"/><path class="n2ffv50qs"/><path class="p2kzhab-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-meter-20" /></template>

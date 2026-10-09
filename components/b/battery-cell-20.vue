<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z79_i2hkx.css';
import '../../css/h/hu2zm7ich.css';
import '../../css/z/zlii3abwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z79_i2hkx"/><path class="hu2zm7ich"/><path class="zlii3abwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-cell-20" /></template>

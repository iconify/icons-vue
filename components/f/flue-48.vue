<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghoh098lm.css';
import '../../css/n/nyhx7fbbv.css';
import '../../css/z/zxrbw5bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ghoh098lm"/><path class="nyhx7fbbv"/><path class="zxrbw5bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flue-48" /></template>

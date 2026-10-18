<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w63goej-d.css';
import '../../css/z/zqrgw3bcs.css';
import '../../css/s/s1299sedn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w63goej-d"/><path class="zqrgw3bcs"/><path class="s1299sedn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drone-inspection-48-bold" /></template>

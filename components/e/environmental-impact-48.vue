<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3b3aw3dq.css';
import '../../css/w/wzf1vhbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j3b3aw3dq"/><path class="wzf1vhbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:environmental-impact-48" /></template>

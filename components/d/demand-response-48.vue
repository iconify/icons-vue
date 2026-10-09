<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs75gccsu.css';
import '../../css/l/leqhccbhf.css';
import '../../css/e/e9wm7acuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zs75gccsu"/><path class="leqhccbhf"/><path class="e9wm7acuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:demand-response-48" /></template>

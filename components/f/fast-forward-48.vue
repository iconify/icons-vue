<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7fb6nbqg.css';
import '../../css/x/xn59nof8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s7fb6nbqg"/><path class="xn59nof8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fast-forward-48" /></template>

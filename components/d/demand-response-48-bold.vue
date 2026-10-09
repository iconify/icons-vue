<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz_20zb_f.css';
import '../../css/x/xotqs1byb.css';
import '../../css/t/teq-8kbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oz_20zb_f"/><path class="xotqs1byb"/><path class="teq-8kbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:demand-response-48-bold" /></template>

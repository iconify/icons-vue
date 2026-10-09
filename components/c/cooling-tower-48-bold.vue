<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhnl4rs5r.css';
import '../../css/c/cj33u3imh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qhnl4rs5r"/><path class="cj33u3imh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cooling-tower-48-bold" /></template>

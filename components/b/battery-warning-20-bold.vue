<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q07t0ebtb.css';
import '../../css/s/sjt-1kaax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q07t0ebtb"/><path class="sjt-1kaax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-warning-20-bold" /></template>

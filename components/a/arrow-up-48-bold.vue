<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2l8ftbhe.css';
import '../../css/p/pjj956y7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i2l8ftbhe"/><path class="pjj956y7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-48-bold" /></template>

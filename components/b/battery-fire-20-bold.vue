<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml5wo9g1f.css';
import '../../css/h/h3y6nxd1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ml5wo9g1f"/><path class="h3y6nxd1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-fire-20-bold" /></template>

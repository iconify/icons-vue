<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5dz5-btu.css';
import '../../css/e/e8z4a313a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r5dz5-btu"/><path class="e8z4a313a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badge-20" /></template>

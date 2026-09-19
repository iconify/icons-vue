<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l43lbubrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="l43lbubrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:bitcoin" /></template>

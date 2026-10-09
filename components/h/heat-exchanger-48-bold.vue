<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbmpiqbiz.css';
import '../../css/r/rcdbnd-dt.css';
import '../../css/w/wbtogqaxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nbmpiqbiz"/><path class="rcdbnd-dt"/><path class="wbtogqaxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-exchanger-48-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm5wywbws.css';
import '../../css/l/l8j0hkazm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wm5wywbws"/><path class="l8j0hkazm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:docked-right" /></template>

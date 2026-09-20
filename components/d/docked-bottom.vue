<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm5wywbws.css';
import '../../css/e/e44nl67iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wm5wywbws"/><path class="e44nl67iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:docked-bottom" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkegzz3bi.css';
import '../../css/h/h07j5abjx.css';
import '../../css/w/ws21njb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hkegzz3bi"/><path class="h07j5abjx"/><path class="ws21njb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hi-vis-vest-48" /></template>

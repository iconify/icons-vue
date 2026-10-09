<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8c1ilbfq.css';
import '../../css/q/qhwpupb8g.css';
import '../../css/j/jhg452mhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o8c1ilbfq"/><path class="qhwpupb8g"/><path class="jhg452mhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lock-keyhole-48" /></template>

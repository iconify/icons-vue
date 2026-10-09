<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b49o_bc6g.css';
import '../../css/b/bbwnydn9j.css';
import '../../css/q/qj6pinbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b49o_bc6g"/><path class="bbwnydn9j"/><path class="qj6pinbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:log-in-48" /></template>

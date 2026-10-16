<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsqs2tb6j.css';
import '../../css/w/w1hy86m-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nsqs2tb6j"/><path class="w1hy86m-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-hybrid-48" /></template>

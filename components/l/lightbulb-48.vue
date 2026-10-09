<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzwzl0bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzwzl0bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lightbulb-48" /></template>
